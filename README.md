<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Cafe</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            font-size: 3rem;
        }
        nav {
            text-align: center;
            background-color: #444;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-size: 1.2rem;
        }
        .section {
            padding: 50px 20px;
            text-align: center;
        }
        .menu-section {
            background-color: #fff;
        }
        .menu-item {
            background-color: #f9f9f9;
            border-radius: 8px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            width: 200px;
            margin: 20px;
            display: inline-block;
            padding: 20px;
        }
        .menu-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
        }
        .menu-item h3 {
            margin-top: 15px;
            font-size: 1.5rem;
        }
        .menu-item p {
            color: #777;
        }
        .menu-item .price {
            font-weight: bold;
            color: #333;
        }
        .reservation-form {
            background-color: #fff;
            max-width: 500px;
            margin: 0 auto;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }
        .reservation-form button {
            background-color: #333;
            color: white;
            padding: 12px;
            border: none;
            width: 100%;
            cursor: pointer;
            border-radius: 5px;
            font-size: 1.1rem;
        }
        .reservation-form button:hover {
            background-color: #555;
        }
        .location-section iframe {
            width: 100%;
            height: 400px;
            border: 0;
            border-radius: 8px;
        }
        .testimonials-section {
            background-color: #f9f9f9;
        }
        .testimonial {
            background-color: #fff;
            margin: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            width: 300px;
            display: inline-block;
            text-align: left;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Cafe Baristo </h1>
        <p>Where flavor meets comfort</p>
    </header>

    <nav>
        <a href="#menu">Menu</a>
        <a href="#reservation">Reservation</a>
        <a href="#location">Location</a>
        <a href="#testimonials">Testimonials</a>
    </nav>

    <!-- Menu Section -->
    <section id="menu" class="section menu-section">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="https://www.allrecipes.com/thmb/Vg2cRidr2zcYhWGvPD8M18xM_WY=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/11973-spaghetti-carbonara-ii-DDMFS-4x3-6edea51e421e4457ac0c3269f3be5157.jpg" alt="Dish 1">
                <h3>Spaghetti Carbonara</h3>
                <p>Classic pasta with creamy sauce and bacon.</p>
                <p class="price">499 inr</p>
            </div>
            <div class="menu-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTIFz1jW_AuCq-ri8jLqcaVGuSsLfSquqxYYg&s" alt="Dish 2">
                <h3>Grilled Chicken Salad</h3>
                <p>Fresh greens with grilled chicken and avocado.</p>
                <p class="price">699 inr</p>
            </div>
            <div class="menu-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSOkN2Vc0CMbhBQbEpTcaZiaA2q_022efEmjg&s" alt="Dish 3">
                <h3>Vegetarian Pizza</h3>
                <p>Tomatoes, cheese, and a variety of fresh vegetables.</p>
                <p class="price">399 inr</p>
            </div>
        </div>
    </section>

    <!-- Reservation Section -->
    <section id="reservation" class="section">
        <h2>Make a Reservation</h2>
        <form class="reservation-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="number" placeholder="Number of People" required>
            <input type="datetime-local" required>
            <textarea placeholder="Special Requests" rows="4"></textarea>
            <button type="submit">Reserve Table</button>
        </form>
    </section>

    <!-- Location Section -->
    <section id="location" class="section">
        <h2>Find Us</h2>
        <iframe src="https://www.google.com/maps/place/Koreean+By+Baristo/data=!4m7!3m6!1s0x3bddedf841371549:0x6464b9533a8ea58b!8m2!3d20.0134065!4d73.7387286!16s%2Fg%2F11k9nynw2h!19sChIJSRU3Qfjt3TsRi6WOOlO5ZGQ?authuser=0&hl=en&rclk=1" allowfullscreen></iframe>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="section testimonials-section">
        <h2>Customer Testimonials</h2>
        <div class="testimonial">
            <p>"The best pasta I've ever had! The service was also excellent." - Emily R.</p>
        </div>
        <div class="testimonial">
            <p>"A hidden gem! The ambiance is perfect for a cozy meal." - John D.</p>
        </div>
        <div class="testimonial">
            <p>"I love the variety in the menu. Always something new to try!" - Sarah W.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Restaurant Cafe. All rights reserved.</p>
    </footer>
</body>
</html>