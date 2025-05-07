# ComputerForce
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - Computer Force</title>
    <link rel="stylesheet" href="style.css">
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}  
</head>
<body>
    <header>
        <h1>Welcome to Computer Force</h1>
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
        <section>
            <h2>Our Products</h2>
            <div class="product">
                <h2>Computers</h2>
                <a href="products.html#computers"><img src="images/computer.jpg" alt="Computers"></a>
            </div>
            <div class="product">
                <h2>Laptops</h2>
                <a href="products.html#laptops"><img src="images/laptop.jpg" alt="Laptops"></a>
            </div>
            <div class="product">
                <h2>Monitors</h2>
                <a href="products.html#monitors"><img src="images/monitor.jpg" alt="Monitors"></a>
            </div>
            <div class="product">
                <h2>Printing & Scanning</h2>
                <a href="products.html#printing"><img src="images/printer.jpg" alt="Printing & Scanning"></a>
            </div>
            <div class="product">
                <h2>Software</h2>
                <a href="products.html#software"><img src="images/software.jpg" alt="Software"></a>
            </div>
            <div class="product">
                <h2>Tablets</h2>
                <a href="products.html#tablets"><img src="images/tablet.jpg" alt="Tablets"></a>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2025 Computer Force. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products - Computer Force</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Products we sell</h1>
        <p>Computer Force sells products in the following categories:</p>
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
        <section id="computers">
            <h2>Computers</h2>
            <img src="images/computer.jpg" alt="Computers">
        </section>
        <section id="laptops">
            <h2>Laptops</h2>
            <img src="images/laptop.jpg" alt="Laptops">
        </section>
        <section id="monitors">
            <h2>Monitors</h2>
            <img src="images/monitor.jpg" alt="Monitors">
        </section>
        <section id="printing">
            <h2>Printing & Scanning</h2>
            <img src="images/printer.jpg" alt="Printing & Scanning">
        </section>
    </main>

    <footer>
        <p>© 2025 Computer Force. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register - Computer Force</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Registration Form</h1>
        <p>Please complete the following form to register for an account on our website.</p>
    </header>

    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="register.html">Register</a></li>
            <li><a href="about.html">About</a></li>
        </ul>
    </nav>

    <form action="#" method="POST">
        <label>Username*: <input type="text" required></label>
        <label>Email*: <input type="email" required></label>
        <label>Password*: <input type="password" required></label>
        <label>Confirm Password*: <input type="password" required></label>
        <label>First Name*: <input type="text" required></label>
        <label>Surname*: <input type="text" required></label>
        <button type="submit">Register</button>
    </form>

    <footer>
        <p>© 2025 Computer Force. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - Computer Force</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>About Computer Force</h1>
        <p>Computer Force is a start-up company providing first-class service...</p>
    </header>
</body>
</html>
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
    text-align: center;
    padding: 20px;
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
main {
    display: grid;
    grid-template-columns: 1fr 3fr;
    gap: 20px;
    padding: 20px;
}
.product {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    margin: 10px;
}

.product img {
    width: 150px;
    height: auto;
    border-radius: 5px;
}
form {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 50%;
    margin: auto;
    display: flex;
    flex-direction: column;
}

form label {
    margin: 10px 0;
}

form input, select {
    width: 100%;
    padding: 8px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    margin-top: 15px;
    padding: 10px;
    background-color: #28a745;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background-color: #218838;
}
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}
