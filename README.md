<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Urban Wardrobe</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Urban Wardrobe</h1>
    <nav>
      <a href="#products">Shop</a>
      <a href="#cart">Cart (<span id="cart-count">0</span>)</a>
    </nav>
  </header>

  <main>
    <section id="products">
      <h2>Our Products</h2>
      <div class="product" data-id="1" data-name="T-Shirt" data-price="20">
        <img src="images/tshirt.jpg" alt="T-Shirt">
        <h3>T-Shirt</h3>
        <p>$20</p>
        <button class="add-to-cart">Add to Cart</button>
      </div>
      <div class="product" data-id="2" data-name="Jeans" data-price="40">
        <img src="images/jeans.jpg" alt="Jeans">
        <h3>Jeans</h3>
        <p>$40</p>
        <button class="add-to-cart">Add to Cart</button>
      </div>
      <!-- Add more products as needed -->
    </section>

    <section id="cart">
      <h2>Your Cart</h2>
      <ul id="cart-items"></ul>
      <p>Total: $<span id="cart-total">0</span></p>
    </section>
  </main>

  <footer>
    <p>© 2024 Urban Wardrobe. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
