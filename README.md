# Login-Form
In this project, I created a transparent login form using HTML and CSS. Login forms are widely used in websites and applications to collect user details and send them for server-side processing.
<!DOCTYPE html>
<html>
<head>
   <title>Transparent Login Form</title>
   <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-12N37f5QGtx?VEgiss14W3ExzMWZxybE1SJSESQP9S+oqd12jhcu+A56EbclzFSJ" crossorigin="anonymous">
   <style>
      body {
         margin: 0;
         padding: 0;
         font-family: sans-serif;
         background-color: lightslategray;
         background-size: cover;
      }
      .login-container{
         width: 280px;
         position: absolute;
         top: 50%;
         left: 50%;
         transform: translate(-50%, -50%);
         color: white;
      }
      .login-box h1{
         border-bottom: 6px solid whitesmoke;
      }
      .textbox{
         width: 100%;
         overflow: hidden;
         font-size: 20px;
         padding: 8px 0;
         margin: 8px 0;
         border-bottom: 1px solid whitesmoke;
      }
      .textbox i {
         width: 26px;
         float: left;
         text-align: center;
      }
      .textbox input{
         border: none;
         outline: none;
         background: none;
         color: white;
         font-size: 18px;
         width: 80%;
         float: left;
         margin: 0 10px;
      }
      .btn{
         width: 100%;
         background: none;
         border: 2px solid whitesmoke;
         color: white;
         padding: 5px;
         font-size: 18px;
         cursor: pointer;
         margin: 12px 0;
      }
      h1{
         text-align: center;
         font-size:x-large;
         padding-bottom: 50px;
         color: purple;
      }
   </style>
</head>
<body>
   <div class="login-container">
      <h1>Tutorialspoint - Login</h1>
      <div class="textbox">
         <i class="fas fa-user"></i>
         <input type="text" placeholder="Username">
      </div>
      <div class="textbox">
         <i class="fas fa-lock"></i>
         <input type="password" placeholder="password">
      </div>
      <input type="button" class="btn" value="Login">
   </div>
</body>
</html>
