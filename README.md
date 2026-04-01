<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ZhesCore</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #201c57, #411a8d, #511c8c);
      color: white;
      text-align: center;
    }

    .container {
      padding: 60px 20px;
    }

    h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    p {
      opacity: 0.8;
    }

    .card {
      margin-top: 30px;
      background: rgba(255,255,255,0.1);
      padding: 20px;
      border-radius: 15px;
      display: inline-block;
      text-align: left;
    }

    .card ul {
      padding-left: 20px;
    }

    .btn {
      margin-top: 20px;
      padding: 10px 20px;
      border: none;
      border-radius: 10px;
      background: #6c2bd9;
      color: white;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #5a22b8;
    }

    footer {
      margin-top: 50px;
      font-size: 12px;
      opacity: 0.6;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>ZhesCore 🚀</h1>
    <p>Advanced WhatsApp Bot & Monitoring System</p>

    <div class="card">
      <h3>🔥 Features</h3>
      <ul>
        <li>Real-time monitoring</li>
        <li>WhatsApp bot automation</li>
        <li>QR login system</li>
        <li>Dashboard analytics</li>
      </ul>
    </div>

    <br>
    <button class="btn" onclick="copyLink()">Copy Website</button>

    <footer>
      © 2026 ZhesCore
    </footer>
  </div>

  <script>
    function copyLink() {
      navigator.clipboard.writeText(window.location.href);
      alert("Link copied!");
    }
  </script>

</body>
</html>
