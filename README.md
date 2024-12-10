<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Hosting Canada</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }

        header {
            background-color: #007bff;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        /* Hero Section */
        .hero {
            background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
            height: 400px;
            display: flex;
            justify-content: flex-end;
            align-items: center;
            color: white;
            text-align: right;
            padding-right: 30px;
        }

        .hero-text h1 {
            font-size: 3rem;
            margin: 0;
        }

        .hero-text p {
            font-size: 1.2rem;
        }

        /* Main Content Section */
        .content {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            margin-top: 20px;
        }

        .card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            width: 30%;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .card h2 {
            color: #007bff;
        }

        .card p {
            font-size: 1.1rem;
        }

        /* Footer Section */
        footer {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .footer-links a, .social-media a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        .social-media i {
            font-size: 30px;
            color: white;
            margin: 0 10px;
        }

        /* Hosting Plans Section */
        .plans {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            padding: 40px;
        }

        .plan {
            background: white;
            padding: 20px;
            border: 1px solid #ddd;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .plan h3 {
            color: #007bff;
        }

        .plan p {
            font-size: 1.1rem;
        }

    </style>
</head>
<body>

    <header>
        <h1><img src="logo.png" alt="Web Hosting Canada Logo" style="height: 40px; vertical-align: middle; margin-right: 10px;"> Web Hosting Canada</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="services.html">Our Services</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="plans.html">Hosting Plans</a></li>
                <li><a href="registration.html">Sign Up</a></li>
                <li><a href="login.html">Login</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-text">
            <h1>Your Trusted Web Hosting Partner</h1>
            <p>Reliable and Affordable Hosting Solutions</p>
        </div>
    </section>

    <!-- Main Content Section -->
    <section class="content">
        <div class="card">
            <h2>Shared Hosting</h2>
            <p>Perfect for small websites and personal blogs. Get started today!</p>
        </div>
        <div class="card">
            <h2>VPS Hosting</h2>
            <p>Powerful and flexible virtual private servers for growing businesses.</p>
        </div>
        <div class="card">
            <h2>Dedicated Hosting</h2>
            <p>Experience unmatched performance with dedicated resources for your enterprise.</p>
        </div>
    </section>

    <!-- Hosting Plans Section -->
    <section class="plans">
        <div class="plan">
            <h3>Basic Plan</h3>
            <p>Price: <strong>$5/month</strong></p>
            <p>Ideal for personal websites and blogs.</p>
        </div>
        <div class="plan">
            <h3>Standard Plan</h3>
            <p>Price: <strong>$10/month</strong></p>
            <p>Perfect for small businesses with moderate traffic.</p>
        </div>
        <div class="plan">
            <h3>Premium Plan</h3>
            <p>Price: <strong>$20/month</strong></p>
            <p>Best for high-traffic websites requiring superior performance.</p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="footer-links">
            <a href="#">Privacy Policy</a>
            <a href="#">Terms of Service</a>
        </div>
        <div class="social-media">
            <a href="https://www.facebook.com/WHC.CA"><i class="fab fa-facebook"></i></a>
            <a href="https://x.com/webhostcanada?mx=2"><i class="fab fa-twitter"></i></a>
            <a href="https://www.instagram.com/whc.ca/"><i class="fab fa-instagram"></i></a>
        </div>
        <p>&copy; 2023 Web Hosting Canada. All rights reserved.</p>
    </footer>

</body>
</html>

