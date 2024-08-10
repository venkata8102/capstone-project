<! DOCTYPE html>
<html leng="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0" >
        <title>venkat web page</title>
        <style type="text/css">
            *{ 
                text-decoration: none;
            }
            .navbar{
                background: crimson; font-family: calibri;padding-right: 15px;padding-left: 15px;
            }
            .navdiv{
                display: flex; align-items: center; justify-content: space-between;
            }
            .logo a{
                font-size: 35px; font-weight: 600; color: azure;
            }
            li{
                list-style: none; display: inline-block;
            }
            li a{
                color: azure;font-size: 18px; font-weight: bold; margin: 25px;
            }
            button{
                background-color: black; margin-left: 10px; border-radius: 10px; padding: 10px; width: 90px;
            }
            button a{
                color: azure; font-weight: bold; font-size: 15px;
            }
         </style>
        </head>
        <body background="C:\Users\USER\OneDrive\New folder\image\b1.jpg">
            <nav class="navbar">
                <div class="logo"><a href="#">Venkat</a></div>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a> </li>
                    <button><a href="#">Signin</a></button>
                    <button><a href="#">Signup</a></button>
                    <li><a href="#">Help and feedback</a></li>
                    </ul>   
            

            </nav>
            
    
            <p align="center"><marquee><h1>jogi.com</h1></marquee></p>
            <form action="/search" method="get">
             <input type="text" name="query" placeholder="search..." size="100px" height="50">
                <input type="submit" value="search" >
              
              
                
</form>
</body>
</html>
