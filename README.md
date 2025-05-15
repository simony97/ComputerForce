<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - Computer Force</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            display: grid;
            grid-template-rows: auto 1fr auto;
            min-height: 100vh;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
        }
        .top-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .user-actions a {
            margin-left: 15px;
            color: white;
            text-decoration: none;
        }
        .cart-icon {
            width: 24px;
            vertical-align: middle;
        }
        nav {
            background-color: #555;
            padding: 10px 0;
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px;
        }
        nav ul li a:hover {
            background-color: #777;
            border-radius: 5px;
        }
        .cta {
            background-color: #004085;
            color: white;
            text-align: center;
            padding: 30px 20px;
            margin: 20px auto;
            border-radius: 10px;
        }
        .cta-button {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background-color: #ffc107;
            color: #000;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
        }
        .cta-button:hover {
            background-color: #e0a800;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
            padding: 20px;
        }
        .product-item {
            background-color: white;
            text-align: center;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .product-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 5px;
        }
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="top-bar">
            <h1>Welcome to Computer Force</h1>
            <div class="user-actions">
                <a href="register.html">Login / Signup</a>
                <a href="#"><img src="images/cart-icon.png" alt="Cart" class="cart-icon"></a>
            </div>
        </div>
        <p>Computer Force is your online expert in all things computing.</p>
    </header>

    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="register.html">Register</a></li>
            <li><a href="about.html">About</a></li>
        </ul>
    </nav>

    <main>
        <section class="product-grid">
            <div class="product-item"><img src="images/computer.jpg" alt="Computers"><h3>Computers</h3></div>
            <div class="product-item"><img src="images/laptop.jpg" alt="Laptops"><h3>Laptops</h3></div>
            <div class="product-item"><img src="images/monitor.jpg" alt="Monitors"><h3>Monitors</h3></div>
            <div class="product-item"><img src="images/printer.jpg" alt="Printers"><h3>Printers</h3></div>
            <div class="product-item"><img src="images/software.jpg" alt="Software"><h3>Software</h3></div>
            <div class="product-item"><img src="images/tablet.jpg" alt="Tablets"><h3>Tablets</h3></div>
            <div class="product-item"><img src="images/accessories.jpg" alt="Accessories"><h3>Accessories</h3></div>
            <div class="product-item"><img src="images/router.jpg" alt="Routers"><h3>Routers</h3></div>
            <div class="product-item"><img src="images/headphones.jpg" alt="Headphones"><h3>Headphones</h3></div>
            <div class="product-item"><img src="images/speakers.jpg" alt="Speakers"><h3>Speakers</h3></div>
            <div class="product-item"><img src="images/keyboard.jpg" alt="Keyboards"><h3>Keyboards</h3></div>
            <div class="product-item"><img src="images/mouse.jpg" alt="Mouse"><h3>Mouse</h3></div>
        </section>
    </main>

    <section class="cta">
        <h2>Connect with our wide range of tech</h2>
        <p>Explore top-notch computers, laptops, accessories, and more!</p>
        <a href="products.html" class="cta-button">Shop Now</a>
    </section>

    <footer>
        <p>© 2025 Computer Force. All rights reserved.</p>
    </footer>
</body>
</html>
