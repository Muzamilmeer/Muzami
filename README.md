
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Muzamil Streetwear</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Orbitron', sans-serif;
      background: #111;
      color: #fff;
    }

    header {
      background: linear-gradient(135deg, #000000, #1f1f1f);
      padding: 20px;
      display: flex;
      align-items: center;
    }

    .logo-img {
      width: 60px;
      height: 60px;
      border-radius: 10px;
      margin-right: 15px;
    }

    .logo-text {
      font-size: 32px;
      color: #00ffff;
      text-shadow: 0 0 5px #00ffff;
    }

    nav {
      text-align: center;
      margin: 20px 0;
    }

    nav a {
      margin: 0 15px;
      color: #00ffff;
      text-decoration: none;
      font-size: 18px;
      transition: 0.3s;
    }

    nav a:hover {
      color: #fff;
    }

    .product-section, .gallery-section, .about-section, .faq-section, .payment-section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .product, .gallery-image {
      background: #222;
      padding: 20px;
      margin-bottom: 30px;
      text-align: center;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,255,255,0.2);
    }

    .product img, .gallery-image img {
      max-width: 300px;
      width: 100%;
      border-radius: 10px;
      margin-bottom: 10px;
    }

    .product h3 {
      color: #00ffff;
      margin-bottom: 10px;
    }

    .product a {
      display: inline-block;
      background: #25D366;
      color: white;
      padding: 10px 20px;
      border-radius: 30px;
      text-decoration: none;
      transition: background 0.3s ease;
    }

    .product a:hover {
      background: #128C7E;
    }

    .faq {
      background: #1c1c1c;
      padding: 20px;
      border-radius: 10px;
    }

    .faq h2, .payment-section h2 {
      color: #00ffff;
      margin-bottom: 20px;
      text-align: center;
    }

    .faq p {
      margin: 10px 0;
    }

    .payment-section img {
      display: block;
      margin: 20px auto;
      max-width: 200px;
      border-radius: 10px;
      box-shadow: 0 0 20px #00ffff;
    }

    footer {
      text-align: center;
      margin: 50px 0 20px;
      color: #aaa;
      font-size: 14px;
    }
  </style>
</head>
<body>

<header>
  <img class="logo-img" src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744286893/IMG_20250403_185247_xzlxll.jpg" alt="Muzamil Logo">
  <div class="logo-text">Muzamil Streetwear</div>
</header>

<nav>
  <a href="#products">Products</a>
  <a href="#gallery">Gallery</a>
  <a href="#about">About</a>
  <a href="#faq">FAQ</a>
  <a href="#payment">Pay</a>
</nav>

<section class="product-section" id="products">
  <div class="product">
    <h3>Urban T-Shirt - ₹499</h3>
    <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744284703/urban-t-shirt-design-614_1080x_pbjxnu.jpg" alt="Urban T-Shirt">
    <a href="https://wa.me/919103594759?text=Hi%2C%20I%20want%20to%20buy%20Urban%20T-Shirt">Buy on WhatsApp</a>
  </div>
  <div class="product">
    <h3>Jordan Shoes - ₹1499</h3>
    <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744284703/image_3_qwbkmd.jpg" alt="Jordan Shoes">
    <a href="https://wa.me/919103594759?text=Hi%2C%20I%20want%20to%20buy%20Jordan%20Shoes">Buy on WhatsApp</a>
  </div>
  <div class="product">
    <h3>Baggy Jeans - ₹799</h3>
    <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744284703/6b9e4944-ff98-4921-9989-afb5bf2518ca1733547766499-DENIMLOOK-Men-Relaxed-Fit-Stretchable-Baggy--Jeans-275173354-2_1_w3mivu.jpg" alt="Baggy Jeans">
    <a href="https://wa.me/919103594759?text=Hi%2C%20I%20want%20to%20buy%20Baggy%20Jeans">Buy on WhatsApp</a>
  </div>
</section>

<section class="gallery-section" id="gallery">
  <div class="gallery-image">
    <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744298764/PhonePeQR_J_K_Grameen_Bank_-_03580_lweegr.png" alt="Gallery 1">
  </div>
</section>

<section class="about-section" id="about">
  <h2>About Us</h2>
  <p style="text-align:center; max-width: 800px; margin:auto;">Muzamil Streetwear is your go-to brand for the freshest urban styles. We bring you quality fashion with a bold neon theme and a modern edge, delivered across India.</p>
</section>

<section class="faq-section" id="faq">
  <div class="faq">
    <h2>FAQ</h2>
    <p><strong>Q:</strong> How to order?<br><strong>A:</strong> Click the WhatsApp button under a product.</p>
    <p><strong>Q:</strong> Do you deliver all over India?<br><strong>A:</strong> Yes, PAN India delivery.</p>
  </div>
</section>

<section class="payment-section" id="payment">
  <h2>Pay with PhonePe</h2>
  <p style="text-align:center;">Scan to Pay</p>
  <img scr="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744298764/PhonePeQR_J_K_Grameen_Bank_-_03580_lweegr.png" alt="PhonePe QR">
</section>

<footer>
  &copy; 2025 Muzamil Streetwear. All rights reserved.
</footer>

</body>
</html>
