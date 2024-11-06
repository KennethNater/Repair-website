<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Phone Repair Services - Schedule appointments and check prices for phone repairs.">
    <title>Phone Repair Services</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header { background-color: #333; color: white; padding: 20px; text-align: center; }
        nav { display: flex; justify-content: center; background-color: #444; }
        nav a { color: white; padding: 14px 20px; text-decoration: none; }
        nav a:hover { background-color: #555; }
        section { padding: 20px; }
        .container { max-width: 800px; margin: 0 auto; }
        h2 { color: #333; }
        .service, .contact-form { border: 1px solid #ddd; padding: 15px; margin-bottom: 20px; }
        footer { text-align: center; padding: 10px; background-color: #333; color: white; margin-top: 20px; }
        .button { display: inline-block; padding: 10px 20px; color: white; background-color: #333; text-decoration: none; }
    </style>
</head>
<body>

<header>
    <h1>Phone Repair Services</h1>
    <p>Quality repairs at affordable prices</p>
</header>

<nav>
    <a href="#services">Services & Pricing</a>
    <a href="#schedule">Schedule Appointment</a>
    <a href="#contact">Contact Us</a>
</nav>

<section id="services">
    <div class="container">
        <h2>Our Services & Pricing</h2>
        <div class="service">
            <h3>Screen Replacement</h3>
            <p>Replace your broken or cracked screen. Price: $100</p>
        </div>
        <div class="service">
            <h3>Battery Replacement</h3>
            <p>Replace your phone's battery for improved performance. Price: $50</p>
        </div>
        <div class="service">
            <h3>Charging Port Repair</h3>
            <p>Fix your phone's charging port. Price: $60</p>
        </div>
        <!-- Add more services as needed -->
    </div>
</section>

<section id="schedule">
    <div class="container">
        <h2>Schedule an Appointment</h2>
        <p>To schedule an appointment, please select a date and time below:</p>
        <!-- Placeholder for Appointment Booking Tool -->
        <p><a href="booking-page.html" class="button">Book an Appointment</a></p>
    </div>
</section>

<section id="contact">
    <div class="container">
        <h2>Contact Us</h2>
        <p>Have questions? Feel free to reach out to us!</p>
        <div class="contact-form">
            <form action="send-email.php" method="POST">
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br><br>

                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>

                <button type="submit" class="button">Send Message</button>
            </form>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Phone Repair Services. All rights reserved.</p>
</footer>

</body>
</html>
