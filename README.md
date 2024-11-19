<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jacket Store</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Jacket Store</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Stylish Jackets for Every Season</h1>
            <p>Stay warm and look great with our exclusive collection.</p>
            <a href="#products" class="btn">Shop Now</a>
        </div>
    </section>

    <section id="products">
        <h2>Our Jackets</h2>
        <div class="product-grid">
            <div class="product">
                <img src="images/jacket1.jpg" alt="Winter Jacket">
                <h3>Winter Jacket</h3>
                <p>$120</p>
                <button class="btn add-to-cart">Add to Cart</button>
            </div>
            <div class="product">
                <img src="images/jacket2.jpg" alt="Leather Jacket">
                <h3>Leather Jacket</h3>
                <p>$150</p>
                <button class="btn add-to-cart">Add to Cart</button>
            </div>
            <div class="product">
                <img src="images/jacket3.jpg" alt="Raincoat">
                <h3>Raincoat</h3>
                <p>$90</p>
                <button class="btn add-to-cart">Add to Cart</button>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We’re passionate about crafting jackets that combine comfort, durability, and style. Shop with confidence and keep warm in any weather.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name</label>
            <input type="text" id="name" placeholder="Your Name" required>
            
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Your Email" required>
            
            <label for="message">Message</label>
            <textarea id="message" placeholder="Your Message" rows="5" required></textarea>
            
            <button type="submit" class="btn">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Jacket Store. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
