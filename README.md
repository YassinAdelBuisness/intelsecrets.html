<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Intel Secrets Template">
    <title>Professional Website</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Basic Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #080808;
        }
        h1, h2, h3 {
            font-weight: normal;
        }

        /* Navigation Bar */
        nav {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: text-decoration: underline;
            padding: 10px 20px;
            margin: 0 10px;
            border-radius: 5px;
        }
        nav a:hover {
            background-color: #ac6969;
        }

        /* Hero Section */
        .hero {
            background-color: #c90c0c;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .hero h1 {
            font-size: 48px;
        }

        /* About Section */
        .about {
            background-color: white;
            padding: 50px 20px;
            text-align: center;
        }

        .about h2 {
            margin-bottom: 20px;
        }

        .about p {
            font-size: 18px;
            max-width: 800px;
            margin: 0 auto;
        }

        /* Services Section */
        .services {
            padding: 50px 20px;
            text-align: center;
            background-color: #f9f9f9;
        }

        .services h2 {
            margin-bottom: 20px;
        }

        .service-card {
            display: inline-block;
            width: 250px;
            padding: 20px;
            background-color: white;
            margin: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        /* Contact Section */
        .contact {
            padding: 50px 20px;
            text-align: center;
            background-color: #333;
            color: white;
        }

        .contact h2 {
            margin-bottom: 20px;
        }

        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact-form button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #45a049;
        }

        /* Footer */
        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 20px;
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Hero Section -->
    <div class="hero" id="home">
        <h1>Welcome to Intel Secrets</h1>
        <p>We provide high-quality services to help you succeed.</p>
    </div>

    <!-- About Section -->
    <section class="about" id="about">
        <h2>About Us</h2>
        <p>We are a professional company offering a range of services designed to help businesses thrive in the digital age. Our team of experts is dedicated to delivering results-driven solutions for every client.</p>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <h2>Our Services</h2>
        <div class="service-card">
            <h3>Web Development</h3>
            <p>Building modern, responsive, and functional websites tailored to your needs.</p>
        </div>
        <div class="service-card">
            <h3>SEO Optimization</h3>
            <p>Improving your website’s visibility and search engine ranking.</p>
        </div>
        <div class="service-card">
            <h3>Digital Marketing</h3>
            <p>Developing strategies to increase your brand’s online presence and engagement.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <form class="contact-form" action="#" method="post">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Intel Secrets. All rights reserved.</p>
    </footer>

</body>
</html>
