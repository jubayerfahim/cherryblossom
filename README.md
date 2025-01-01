# cherryblossom<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cherry Blossom - Cosmetics</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="navbar">
        <div class="logo">Cherry Blossom</div>
        <nav>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Welcome to Cherry Blossom</h1>
        <p>Discover the best cosmetics for your beauty needs.</p>
        <button onclick="shopNow()">Shop Now</button>
    </section>

    <section id="products" class="products">
        <h2>Our Products</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="lipstick.jpg" alt="Lipstick">
                <h3>Lipstick</h3>
                <p>$10</p>
            </div>
            <div class="product-card">
                <img src="foundation.jpg" alt="Foundation">
                <h3>Foundation</h3>
                <p>$20</p>
            </div>
            <div class="product-card">
                <img src="eyeshadow.jpg" alt="Eyeshadow">
                <h3>Eyeshadow</h3>
                <p>$15</p>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>At Cherry Blossom, we believe in enhancing your natural beauty with quality cosmetics. Our products are crafted with care and love.</p>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer class="footer">
        <p>© 2025 Cherry Blossom. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
You sent
body {
    margin: 0;
    font-family: Arial, sans-serif;
    color: #333;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #ffcccb;
}

.navbar .logo {
    font-size: 24px;
    font-weight: bold;
    color: #fff;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

.nav-links a {
    text-decoration: none;
    color: #fff;
    font-size: 18px;
}

.hero {
    text-align: center;
    padding: 100px 20px;
    background: linear-gradient(to right, #ffcccb, #ffc0cb);
    color: #fff;
}

.hero button {
    padding: 10px 20px;
    background-color: #fff;
    color: #ff6666;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.products {
    padding: 50px 20px;
    text-align: center;
}

.product-grid {
    display: flex;
    gap: 20px;
    justify-content: center;
    flex-wrap: wrap;
}

.product-card {
    width: 200px;
    border: 1px solid #ddd;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 10px;
}

.product-card img {
    width: 100%;
    height: auto;
}

.about, .contact {
    padding: 50px 20px;
    text-align: center;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #ffcccb;
    color: #fff;
}
You sent
function shopNow() {
    alert("Welcome to Cherry Blossom! Explore our products.");
}

// Contact form submission
document.getElementById('contact-form').addEventListener('submit', function (event) {
    event.preventDefault();
    alert("Thank you for contacting us! We'll get back to you soon.");
});
