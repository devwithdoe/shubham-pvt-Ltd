<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shubham Pvt. Ltd. | Hardware Store</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }

    header {
      background: linear-gradient(90deg, #1a73e8, #004aad);
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.2em;
    }

    nav {
      background: #333;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 10px 20px;
      margin: 0 10px;
      transition: background 0.3s;
    }

    nav a:hover {
      background: #1a73e8;
      border-radius: 5px;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1601049676869-702ea24cfd54') center/cover no-repeat;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.7);
      font-size: 2em;
      font-weight: bold;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }

    .product {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
      transition: transform 0.3s;
    }

    .product:hover {
      transform: translateY(-5px);
    }

    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .product h3 {
      margin: 10px 0;
      color: #333;
    }

    .product p {
      color: #666;
      font-size: 14px;
      margin-bottom: 10px;
    }

    .product button {
      background: #1a73e8;
      color: white;
      border: none;
      padding: 10px 20px;
      margin-bottom: 15px;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }

    .product button:hover {
      background: #004aad;
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Shubham Pvt. Ltd.</h1>
    <p>Your Trusted Online Hardware Store</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">About Us</a>
    <a href="#">Contact</a>
  </nav>

  <section class="hero">
    Premium Quality Tools & Hardware at Best Prices!
  </section>

  <section class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1581090700227-1e37b190418e" alt="Hammer">
      <h3>Steel Hammer</h3>
      <p>Durable and heavy-duty hammer for construction work.</p>
      <button>Buy Now</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1606813909477-fd5246d4f87a" alt="Screwdriver Set">
      <h3>Screwdriver Set</h3>
      <p>Precision tools for home and professional use.</p>
      <button>Buy Now</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1581093588401-22d8d4f9b907" alt="Drill Machine">
      <h3>Drill Machine</h3>
      <p>Powerful electric drill for all kinds of projects.</p>
      <button>Buy Now</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Shubham Pvt. Ltd. | All Rights Reserved</p>
  </footer>
</body>
</html>
