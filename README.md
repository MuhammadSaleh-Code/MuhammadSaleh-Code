<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Electronic Brand</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Electronic Brand</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#phones">Phones</a></li>
                    <li><a href="#watches">Watches</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <section id="home" class="hero">
        <div class="container">
            <h2>Welcome to Electronic Brand</h2>
            <p>Explore the latest phones and watches.</p>
        </div>
    </section>
    
    <section id="phones" class="products">
        <div class="container">
            <h2>Phones</h2>
            <div class="product-list">
                <div class="product">
                    <img src="phone1.jpg" alt="Phone 1">
                    <h3>Phone Model 1</h3>
                    <p>$499.99</p>
                </div>
                <div class="product">
                    <img src="phone2.jpg" alt="Phone 2">
                    <h3>Phone Model 2</h3>
                    <p>$699.99</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="watches" class="products">
        <div class="container">
            <h2>Watches</h2>
            <div class="product-list">
                <div class="product">
                    <img src="watch1.jpg" alt="Watch 1">
                    <h3>Watch Model 1</h3>
                    <p>$199.99</p>
                </div>
                <div class="product">
                    <img src="watch2.jpg" alt="Watch 2">
                    <h3>Watch Model 2</h3>
                    <p>$299.99</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>We provide the best electronic products in the market. Our mission is to offer high-quality electronics at affordable prices.</p>
        </div>
    </section>
    
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <p>&copy; 2024 Electronic Brand. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
