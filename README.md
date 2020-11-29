# Testproject

</html>
 <head>Mayur19</head>
       <script src="http://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc=" crossorigin="anonymous"></script>
        <script>
//callback function ---- > event handler
            $(document).ready(function(){

                $("#btn").click(function()
                {

                   $("table").fadeToggle(
                    $("table").css({
                            "background-color":"cyan"
                        })
                   );

               
                   $("table").fadeToggle(
                    $("table").css({
                            "background-color":"yellow"
                        })
                   );

                });
                   
           

            });
        </script>
    
    <body>
       
        <table border="2" ">
            <tr><th>Product id</th><th>product name</th><th>price</th></tr>
            <tr><td>101</td><td ><p>Table</p></td><td>2000</td></tr>
            <tr><td>1</td><td ><p>Chair</p></td><td>1000</td></tr>
            <tr><td>11</td><td ><p>Door</p></td><td>31500</td></tr>
            <tr><td>31</td><td ><p>window</p></td><td>3000</td></tr>
        </table>
   
      <button type="button" name="btn" id="btn" >click Here</button>
    </body>
</html>
