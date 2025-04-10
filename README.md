<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Commodity Export</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f5f9f6;
      color: #333;
    }
    header {
      background-color: #1d4734;
      color: white;
      padding: 20px 40px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    header img {
      height: 60px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1542831371-29b0f74f9713') center/cover no-repeat;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.5);
      font-size: 36px;
      font-weight: bold;
    }
    .section {
      padding: 40px;
      text-align: center;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }
    .product {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      width: 250px;
      padding: 20px;
    }
    .product img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }
    footer {
      background-color: #1d4734;
      color: white;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <img src="1000097772.png" alt="Commodity Export Logo">
    <nav>
      <a href="#products">Products</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    Bringing Indonesia's Finest Commodities to the World
  </div>

  <section id="products" class="section">
    <h2>Our Products</h2>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1572438536140-9b4efb1f8223" alt="Coconut">
        <h3>Fresh Coconut</h3>
        <p>Premium coconuts directly from Indonesian farms.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1585238342023-2784f0d7fcb7" alt="Coffee Beans">
        <h3>Coffee Beans</h3>
        <p>Aromatic coffee sourced from Sumatra and Java.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1600690561764-f7408dba4b89" alt="Spices">
        <h3>Indonesian Spices</h3>
        <p>Cloves, nutmeg, cinnamon, and more—export quality.</p>
      </div>
    </div>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>
      We are a trusted export company based in Indonesia, specializing in natural
      agricultural commodities. With a commitment to sustainability and quality,
      we connect local farmers to global markets.
    </p>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: info@commodityexport.id</p>
    <p>WhatsApp: +62 812 3456 7890</p>
  </section>

  <footer>
    &copy; 2025 Commodity Export. All rights reserved.
  </footer>
</body>
</html>

