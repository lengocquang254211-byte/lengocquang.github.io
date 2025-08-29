<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lê Ngọc Quảng</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: #fff;
      text-align: center;
      overflow-x: hidden;
    }

    header {
      padding: 50px 20px 20px;
      animation: fadeIn 2s ease-in-out;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 10px;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.3);
    }

    p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    .social-links {
      margin: 40px 0;
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
    }

    .social-links a {
      display: inline-block;
      padding: 15px 25px;
      border-radius: 30px;
      background: rgba(255,255,255,0.15);
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1rem;
      backdrop-filter: blur(5px);
      transition: 0.3s;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }

    .social-links a:hover {
      background: rgba(255,255,255,0.35);
      transform: scale(1.1);
    }

    footer {
      margin-top: 50px;
      padding: 20px;
      font-size: 0.9rem;
      opacity: 0.7;
    }

    /* Hiệu ứng mượt */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>✨ Lê Ngọc Quảng ✨</h1>
    <p>Chào mừng bạn đến với trang cá nhân của mình!</p>
  </header>

  <section class="social-links">
    <a href="https://www.facebook.com/le.ngoc.quang.172073" target="_blank">📘 Facebook</a>
    <a href="https://www.tiktok.com/@icecreamlanhlung" target="_blank">🎵 TikTok</a>
    <a href="https://www.instagram.com/doi_te_vcl" target="_blank">📸 Instagram</a>
  </section>

  <footer>
    © 2025 - Thiết kế bởi Lê Ngọc Quảng
  </footer>
</body>
</html>
