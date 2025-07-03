<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rokien - Print-on-Demand Store</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background: #f4f7fa;
      color: #333;
    }
    header {
      background-color: #1f3b73;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #334e9b;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: inline-block;
    }
    nav a:hover {
      background-color: #2a3e7c;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.2s;
      text-decoration: none;
      color: inherit;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card-content {
      padding: 15px;
    }
    .card-content h3 {
      margin: 0 0 10px;
    }
    .card-content button {
      background-color: #1f3b73;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    .card-content button:hover {
      background-color: #152a57;
    }
  </style>
</head>
<body>
  <header>
    <h1>Rokien</h1>
    <p>Your All-in-One Print-on-Demand Store</p>
  </header>
  <nav>
    <a href="#">T-Shirts</a>
    <a href="#">Mugs</a>
    <a href="#">Phone Covers</a>
    <a href="#">Bags</a>
    <a href="#">Raksha Bandhan</a>
    <a href="#">Goggles</a>
  </nav>
  <div class="container">
    <a class="card" href="https://rokien.myshopify.com/products/modern-blue-tee" target="_blank">
      <img src="https://via.placeholder.com/300x200?text=T-Shirt" alt="T-Shirt">
      <div class="card-content">
        <h3>Modern Blue Tee</h3>
        <button>Buy Now</button>
      </div>
    </a>
    <a class="card" href="https://rokien.myshopify.com/products/calm-vibes-mug" target="_blank">
      <img src="https://via.placeholder.com/300x200?text=Mug" alt="Mug">
      <div class="card-content">
        <h3>Calm Vibes Mug</h3>
        <button>Buy Now</button>
      </div>
    </a>
    <a class="card" href="https://rokien.myshopify.com/products/abstract-phone-cover" target="_blank">
      <img src="https://via.placeholder.com/300x200?text=Phone+Cover" alt="Phone Cover">
      <div class="card-content">
        <h3>Abstract Phone Cover</h3>
        <button>Buy Now</button>
      </div>
    </a>
    <a class="card" href="https://rokien.myshopify.com/products/urban-utility-bag" target="_blank">
      <img src="https://via.placeholder.com/300x200?text=Bag" alt="Bag">
      <div class="card-content">
        <h3>Urban Utility Bag</h3>
        <button>Buy Now</button>
      </div>
    </a>
    <a class="card" href="https://rokien.myshopify.com/products/rakhi-special-combo" target="_blank">
      <img src="https://via.placeholder.com/300x200?text=Raksha+Bandhan" alt="Raksha Bandhan">
      <div class="card-content">
        <h3>Rakhi Special Combo</h3>
        <button>Buy Now</button>
      </div>
    </a>
    <a class="card" href="https://rokien.myshopify.com/products/summer-style-goggles" target="_blank">
      <img src="https://via.placeholder.com/300x200?text=Goggles" alt="Goggles">
      <div class="card-content">
        <h3>Summer Style Goggles</h3>
        <button>Buy Now</button>
      </div>
    </a>
  </div>
</body>
</html>
