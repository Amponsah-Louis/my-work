<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Luxury Phone Shop</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto:wght@400;500&display=swap"
      rel="stylesheet"
    />
    <style>
      /* General Styles */
      body {
        font-family: 'Roboto', sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f9;
        color: #333;
        line-height: 1.6;
      }

      .container {
        width: 90%;
        max-width: 1200px;
        margin: 0 auto;
      }

      h1,
      h2,
      h3 {
        font-family: 'Playfair Display', serif;
      }

      /* Header */
      .header {
        background: linear-gradient(135deg, #1e3c72, #2a5298);
        color: #fff;
        padding: 80px 0;
        text-align: center;
      }

      .header h1 {
        font-size: 4rem;
        margin: 0;
      }

      .header p {
        font-size: 1.5rem;
        margin: 10px 0 0;
      }

      /* Navigation */
      .navbar {
        background: #333;
        padding: 20px 0;
      }

      .navbar ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
      }

      .navbar ul li {
        margin: 0 20px;
      }

      .navbar ul li a {
        color: #fff;
        text-decoration: none;
        font-size: 1.1rem;
        font-weight: 500;
      }

      .navbar ul li a:hover {
        color: #ffd700;
      }

      /* Hero Section */
      .hero {
        background: url('https://via.placeholder.com/1500x600') no-repeat center
          center/cover;
        color: #fff;
        padding: 150px 0;
        text-align: center;
      }

      .hero h2 {
        font-size: 3rem;
        margin: 0;
      }

      .hero p {
        font-size: 1.5rem;
        margin: 20px 0;
      }

      .hero .btn {
        background: #ffd700;
        color: #333;
        padding: 12px 24px;
        text-decoration: none;
        border-radius: 5px;
        font-size: 1.1rem;
        font-weight: 500;
      }

      .hero .btn:hover {
        background: #e6b800;
      }

      /* Products Section */
      .products {
        padding: 80px 0;
        background: #fff;
      }

      .products h2 {
        text-align: center;
        font-size: 3rem;
        margin-bottom: 40px;
      }

      .product-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 30px;
      }

      .product-card {
        background: #fff;
        border: 1px solid #ddd;
        border-radius: 10px;
        padding: 20px;
        text-align: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease;
      }

      .product-card:hover {
        transform: translateY(-10px);
      }

      .product-card img {
        max-width: 100%;
        border-radius: 10px;
      }

      .product-card h3 {
        font-size: 1.5rem;
        margin: 15px 0 10px;
      }

      .product-card p {
        font-size: 1.2rem;
        color: #333;
      }

      .product-card .btn {
        background: #333;
        color: #fff;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-size: 1rem;
      }

      .product-card .btn:hover {
        background: #555;
      }

      /* About Section */
      .about {
        padding: 80px 0;
        background: #f4f4f9;
        text-align: center;
      }

      .about h2 {
        font-size: 3rem;
        margin-bottom: 20px;
      }

      .about p {
        font-size: 1.2rem;
        max-width: 800px;
        margin: 0 auto;
      }

      /* Contact Section */
      .contact {
        padding: 80px 0;
        background: #fff;
        text-align: center;
      }

      .contact h2 {
        font-size: 3rem;
        margin-bottom: 20px;
      }

      .contact form {
        max-width: 600px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
        gap: 15px;
      }

      .contact input,
      .contact textarea {
        padding: 12px;
        border: 1px solid #ddd;
        border-radius: 5px;
        font-size: 1rem;
      }

      .contact .btn {
        background: #333;
        color: #fff;
        padding: 12px 24px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-size: 1.1rem;
      }

      .contact .btn:hover {
        background: #555;
      }

      /* Footer */
      .footer {
        background: #333;
        color: #fff;
        padding: 20px 0;
        text-align: center;
      }

      .footer p {
        margin: 0;
        font-size: 1rem;
      }
    </style>
  </head>
  <body>
    <!-- Header -->
    <header class="header">
      <div class="container">
        <h1>Luxury Phone Shop</h1>
        <p>Where Innovation Meets Elegance</p>
      </div>
    </header>

    <!-- Navigation -->
    <nav class="navbar">
      <div class="container">
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#products">Products</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
      <div class="container">
        <h2>Discover the Future of Luxury</h2>
        <p>Explore our exclusive collection of high-end smartphones.</p>
        <a href="#products" class="btn">Shop Now</a>
      </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="products">
      <div class="container">
        <h2>Our Collection</h2>
        <div class="product-grid">
          <div class="product-card">
            <img src="c:\New folder\1.jpg" alt="iPhone 15" />
            <h3>iPhone 15 Pro Max</h3>
            <p>$1,199</p>
            <button class="btn">Add to Cart</button>
          </div>
          <div class="product-card">
            <img
              src="c:\New folder\2.jpg"
              alt="Samsung Galaxy S23"
            />
            <h3>Samsung Galaxy S23 Ultra</h3>
            <p>$1,099</p>
            <button class="btn">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="c:\New folder\3.jpg" alt="Google Pixel 8" />
            <h3>Google Pixel 8 Pro</h3>
            <p>$999</p>
            <button class="btn">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="c:\New folder\4.jpg" alt="OnePlus 11" />
            <h3>OnePlus 11</h3>
            <p>$799</p>
            <button class="btn">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="c:\New folder\6.jpg" alt="iPhone 16" />
            <h3>iPhone 16</h3>
            <p>$3,799</p>
            <button class="btn">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="c:\New folder\7.jpg" alt="Tecno Camon 40" />
            <h3>Tecno Camon 40</h3>
            <p>$1,799</p>
            <button class="btn">Add to Cart</button>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
      <div class="container">
        <h2>About Us</h2>
        <p>
          Luxury Phone Shop is your premier destination for the finest smartphones
          in the world. We curate only the most exclusive, high-performance
          devices to elevate your lifestyle.
        </p>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
      <div class="container">
        <h2>Contact Us</h2>
        <p>Have questions? We're here to help!</p>
        <form>
          <input type="text" placeholder="Your Name" required />
          <input type="email" placeholder="Your Email" required />
          <textarea placeholder="Your Message" required></textarea>
          <button type="submit" class="btn">Send Message</button>
        </form>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="container">
        <p>&copy; 2023 Luxury Phone Shop. All rights reserved.</p>
      </div>
    </footer>
  </body>
</html>
