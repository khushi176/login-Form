# login-Form
<!DOCTYPE html>
<html>
    <head>
        <title>Login</title>
        <style>
            body{display: flex;
                justify-content: center;
            align-items: center;
        min-height: 100vh;
    background: black;}
    form{
        justify-content: center;
        align-items: center;
        position: relative;
    width: 300px;
background: black;
box-shadow: 0 0 50px rgb(2, 156, 212);
border-radius: 20px;
padding: 40px;
}
  input{display: flex;
 width: 100%;
height: 40px;
border-radius: 20px;
background: transparent;
color:white
}
 
label{display: flex;
  justify-content:center;
  width: 100%;  
  gap:4px;
margin-top: 10px;
margin-bottom: 10px;}
button{justify-content: center;
align-items: center;
margin-left: 128px;
border-width:10px;;
border-radius: 10px;}
.remember{font-size: medium;
color:white;
padding-right: 150px
}


    </style>
    </head>
    <body>
        <form id="result form" >
            <h1 style="text-align: center; color:white">LOGIN</h1>
        <label text-align="center"><br>
        <input type="text" id="Username" required placeholder="Username">
        </label> 
        <label text-align="center"><br>
            <input type="password" id="password" required placeholder="password"><br>
        </label>
       <div class="remember">
        <label for="remember">
            <input type="checkbox" style="scale: 0.7;">Remember Me
        </label>
        </div>
        <a href="projecthtml.html" target="_blank">
        <button type="submit" >Log In</button><br>
        </a>
        <div class="signup-link">
            <p style="color: white;">Don't Have An Account ? <a href="#" class="signup-link">Sign Up</a></p>
        </div>
        </form>
    </body>
</html>
