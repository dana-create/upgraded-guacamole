# upgraded-guacamole
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
    <style>
      nav{
      box-sizing:border box;
      border:bold;
      width:100%;
      height:50px;
        background-color:none;
        color:#F0F8FF;
        padding:5px;
        border-radius:10px;
        text-align:center;
        font-size:50px;
      
      }
      .one{
        font-family:Comic Sans MS;
        text-align:center;
       
        
      }
      p{
        border:block;
        border-radius:25px;
        text-align:center;
         color:white;
        padding:100px;
        height:50px;
      }
      body{
        background-image:url("https://wallpaperaccess.com/full/1206393.jpg");
      }
      button{
        border:block;
        border-radius:5px;
        padding:2%;
        width:175px;
        background-color:#F5F5F5;
      }
    </style>
  </head>
  <body>
  <div class="one">
    <nav><h1>InstaMug</h1></nav>
    <p>We serve because you love it.</p>
    <button>Lets Get Started</button>
     <button onclick="myFunction()">
       <a href="/part2.html">Login</a>
     </button>
     
  </div>

   <script>
     function myFunction() {
 var myWindow = window.open("/.part2.html/", "_self");
myWindow.document.write("<p>I replaced the current window.</p>");
}
let response = await fetch(/part2.h);//fetch another page eg battery.html
    content.innerHTML = await response.text();
    executeScripts();
  }
    </script>

  </body>
</html>
