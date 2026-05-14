<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

  <title>Website Coming Soon</title>

  <style>

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      background:linear-gradient(135deg,#111,#1e1e1e,#000);
      font-family:Arial,sans-serif;
      color:white;
      overflow:hidden;
    }

    .container{
      text-align:center;
      background:rgba(255,255,255,0.05);
      padding:50px;
      border-radius:20px;
      backdrop-filter:blur(10px);
      box-shadow:0 0 30px rgba(0,0,0,0.5);
      animation:fade 1s ease;
    }

    h1{
      font-size:55px;
      margin-bottom:10px;
      color:#00ffd5;
      text-shadow:0 0 15px #00ffd5;
    }

    p{
      font-size:18px;
      color:#ccc;
      margin-bottom:30px;
    }

    .error{
      color:#ff4d4d;
      font-weight:bold;
      margin-bottom:25px;
      font-size:20px;
    }

    button{
      padding:14px 30px;
      border:none;
      border-radius:12px;
      font-size:18px;
      cursor:pointer;
      background:#00ffd5;
      color:#000;
      font-weight:bold;
      transition:0.3s;
    }

    button:hover{
      transform:scale(1.08);
      box-shadow:0 0 20px #00ffd5;
    }

    .footer{
      margin-top:25px;
      font-size:14px;
      color:#777;
    }

    @keyframes fade{
      from{
        opacity:0;
        transform:translateY(20px);
      }

      to{
        opacity:1;
        transform:translateY(0);
      }
    }

  </style>
</head>

<body>

  <div class="container">

    <h1>Frozen</h1>

    <p>Website is currently unavailable</p>

    <div class="error">
      ERROR 991
    </div>

    <button onclick="hello()">
      Click Here
    </button>

    <div class="footer">
      © 2026 Frozen Studio
    </div>

  </div>

  <script>

    function hello(){
      alert("Cảm ơn bạn đã truy cập website!");
    }

  </script>

</body>
</html>