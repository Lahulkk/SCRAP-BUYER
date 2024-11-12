# SCRAP-BUYER <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scrap Buyer</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Scrap Buyer Services</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Home Section -->
    <section id="home" class="section">
        <div class="container">
            <h2>Welcome to Scrap Buyer</h2>
            <p>Your trusted partner for buying scrap metal, electronics, and other recyclable materials. We offer reliable, eco-friendly, and efficient services to make your scrap disposal hassle-free.</p>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="section">
        <div class="container">
            <h2>Our Services</h2>
            <div class="service-item">
                <h3>Metal Scrap</h3>
                <p>We buy all types of metal scrap including aluminum, copper, steel, and iron. Get the best rates for your metal waste.</p>
            </div>
            <div class="service-item">
                <h3>Electronic Waste</h3>
                <p>We offer a responsible and eco-friendly way to dispose of your old electronics like phones, laptops, and appliances.</p>
            </div>
            <div class="service-item">
                <h3>Plastic & Paper Waste</h3>
                <p>We purchase plastic and paper waste, ensuring proper recycling and reducing environmental impact.</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <h2>About Us</h2>
            <p>Scrap Buyer is a leading scrap collection service dedicated to offering the best prices for your recyclable materials. We are committed to providing sustainable and eco-friendly solutions, while also contributing to the reduction of waste and energy use.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Us</h2>
            <p>If you have scrap materials to sell or need more information, feel free to reach out to us. We are here to assist you!</p>
            <form action="submit_form.php" method="POST">
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                
                <button type="submit">Submit</button>
            </form>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Scrap Buyer. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
