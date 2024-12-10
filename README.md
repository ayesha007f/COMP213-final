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

        .contact-info {
            display: none;
            position: absolute;
            background-color: #007bff;
            color: white;
            padding: 10px;
            border-radius: 5px;
            top: 30px;
            left: 0;
            width: 200px;
            z-index: 100;
        }

        .contact-link:hover + .contact-info {
            display: block;
        }

        footer {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .social-media i {
            font-size: 30px;
            color: white;
            margin: 0 10px;
        }

        .footer-links a,
        .social-media a {
            color: white;
            text-decoration: none;
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
                <li><a href="contact.html" class="contact-link">Contact Us</a></li>
                <li><a href="plans.html">Hosting Plans</a></li>
                <li><a href="registration.html">Sign Up</a></li>
                <li><a href="login.html">Login</a></li>
            </ul>
        </nav>
        <div class="contact-info">
            <p>Email: contact@webhostingcanada.com</p>
            <p>Phone: 1-800-123-4567</p>
        </div>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h1>Your Trusted Web Hosting Partner</h1>
            <p>Reliable and Affordable Hosting Solutions</p>
        </div>
    </section>

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
        <p> Ayesha Ftaima - 301452624 | COMP213 - Individual Assignment
    </footer>

</body>
</html>
