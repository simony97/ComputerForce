Completed website activity 3

Index
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Home - Computer Force</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Computer Force</h1>
    </header>
    <main>
        <p>Computer Force is your online expert in all things computing.</p>

        <h2>Computers</h2>
        <a href="products.html#computers"><img src="images/computers.jpg" alt="Computers"></a>

        <h2>Laptops</h2>
        <a href="products.html#laptops"><img src="images/laptops.jpg" alt="Laptops"></a>

        <h2>Monitors</h2>
        <a href="products.html#monitors"><img src="images/monitors.jpg" alt="Monitors"></a>

        <h2>Printing & scanning</h2>
        <a href="products.html#printing"><img src="images/printing.jpg" alt="Printing and Scanning"></a>

        <h2>Software</h2>
        <a href="products.html#software"><img src="images/software.jpg" alt="Software"></a>

        <h2>Tablets</h2>
        <a href="products.html#tablets"><img src="images/tablets.jpg" alt="Tablets"></a>
    </main>
    <footer>
        <p>&copy; 2025 Computer Force</p>
    </footer>
</body>
</html>

Products
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Products - Computer Force</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Products we sell</h1>
    </header>
    <main>
        <p>Computer Force sells products in the following categories:</p>

        <h2 id="audio">Audio</h2>
        <img src="images/audio.jpg" alt="Audio">

        <h2 id="computers">Computers</h2>
        <img src="images/computers.jpg" alt="Computers">

        <h2 id="graphics">Graphics cards</h2>
        <img src="images/graphics.jpg" alt="Graphics cards">

        <h2 id="keyboard">Keyboard and mice</h2>
        <img src="images/keyboard.jpg" alt="Keyboard and mice">

        <h2 id="laptops">Laptops</h2>
        <img src="images/laptops.jpg" alt="Laptops">

        <h2 id="monitors">Monitors</h2>
        <img src="images/monitors.jpg" alt="Monitors">

        <h2 id="networking">Networking</h2>
        <img src="images/networking.jpg" alt="Networking">

        <h2 id="peripherals">Peripherals</h2>
        <img src="images/peripherals.jpg" alt="Peripherals">

        <h2 id="printing">Printing & scanning</h2>
        <img src="images/printing.jpg" alt="Printing & scanning">

        <h2 id="software">Software</h2>
        <img src="images/software.jpg" alt="Software">

        <h2 id="storage">Storage</h2>
        <img src="images/storage.jpg" alt="Storage">

        <h2 id="tablets">Tablets</h2>
        <img src="images/tablets.jpg" alt="Tablets">
    </main>
    <footer>
        <p>&copy; 2025 Computer Force</p>
    </footer>
</body>
</html>

Register
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Register - Computer Force</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <img src="images/logo.png" alt="Computer Force logo" />
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="register.html">Register</a></li>
        <li><a href="about.html">About</a></li>
      </ul>
    </nav>
  </header>

  <section class="cta-banner">
    <h2>Connect with our wide range of tech</h2>
  </section>

  <main>
    <h1>Register with Computer Force</h1>
    <form action="#" method="post">
      <label for="fullname">Full Name:</label>
      <input type="text" id="fullname" name="fullname" required />

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required />

      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required />

      <label for="gender">Gender:</label>
      <select id="gender" name="gender" required>
        <option value="" disabled selected>Select gender</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
      </select>

      <label for="state">State:</label>
      <select id="state" name="state" required>
        <option value="" disabled selected>Select state</option>
        <option value="ACT">ACT</option>
        <option value="NSW">NSW</option>
        <option value="NT">NT</option>
        <option value="QLD">QLD</option>
        <option value="SA">SA</option>
        <option value="TAS">TAS</option>
        <option value="VIC">VIC</option>
        <option value="WA">WA</option>
      </select>

      <label for="interests">Interests:</label>
      <textarea id="interests" name="interests" rows="4" placeholder="Tell us about your interests..."></textarea>

      <button type="submit">Register</button>
    </form>
  </main>

  <aside>
    <h3>Need Help?</h3>
    <p>Contact our support team for assistance with registration.</p>
  </aside>

  <footer>
    <p>&copy; 2025 Computer Force. Website developed by Simony Batista.</p>
    <p>Opening Hours: Mon–Fri, 9am–5pm</p>
  </footer>
</body>
</html>

About
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>About - Computer Force</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>About Computer Force</h1>
    </header>
    <main>
        <p>Computer Force is a brand-new start-up company designed to provide the first-class service to its customers. Based in Parramatta in Sydney, Computer Force provides top-class computing products at bargain prices, for sale throughout Australia.</p>

        <p>Our goals are:</p>
        <ul>
            <li>To become Australia’s most well-known and respected hardware and software, provider</li>
            <li>To create a service-based organisation whose goal is to exceed customer's expectations</li>
            <li>To provide a smooth, efficient, and transparent sales process</li>
        </ul>

        <p>You can contact us using the following methods:</p>
        <p>Address: 100 Main Road, Parramatta, NSW 20150</p>
        <p>Email: info@computerforce.com.au</p>
        <p>Phone: 02 4444 5555</p>
    </main>
    <footer>
        <p>&copy; 2025 Computer Force</p>
    </footer>
</body>
</html>

styles.css 
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header, footer {
    background-color: #004080;
    color: white;
    text-align: center;
    padding: 1em;
}

main {
    padding: 20px;
}

h1, h2 {
    color: #004080;
}

img {
    width: 200px;
    height: auto;
    display: block;
    margin-bottom: 20px;
}
