# Login-page-mikrotix
Templet login page
<!DOCTYPE html>
<html>
<head>
  <title>Login Hotspot - THREE.ID</title>
  <meta charset="UTF-8" />
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom right, #ff0000, #ffffff);
      margin: 0;
      padding: 0;
    }

    .login-box {
      max-width: 320px;
      background: white;
      padding: 20px;
      border-radius: 10px;
      margin: 80px auto;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      text-align: center;
    }

    .login-box h2 {
      margin-bottom: 20px;
      color: #ff0000;
    }

    input[type="text"], input[type="password"] {
      width: 90%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    input[type="submit"] {
      width: 100%;
      padding: 10px;
      background-color: #ff0000;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }

    input[type="submit"]:hover {
      background-color: #cc0000;
    }

    .footer {
      margin-top: 15px;
      font-size: 12px;
      color: #666;
    }
  </style>
</head>
<body>

  <div class="login-box">
    <h2>3THREE.ID Hotspot</h2>
    <form name="login" action="$(link-login-only)" method="post">
      <input type="hidden" name="dst" value="$(link-orig)" />
      <input type="hidden" name="popup" value="true" />
      <input type="text" name="username" placeholder="Username" />
      <input type="password" name="password" placeholder="Password" />
      <input type="submit" value="Login" />
    </form>
    <div class="footer">
      PT. Awinet Gelobal Mandiri
    </div>
  </div>

</body>
</html>
