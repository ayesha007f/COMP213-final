<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Hosting Canada</title>
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

        .hero {
            background: url('https://th.bing.com/th/id/R.86a13275fe3e6d5e3feb439c254f1980?rik=CuDcpL0Lu5aqWQ&riu=http%3a%2f%2fak9.picdn.net%2fshutterstock%2fvideos%2f5227409%2fthumb%2f1.jpg&ehk=Uk0MlLhKhXOaYmqEooA6mMuOx8yPXD7dIyINq%2bos31U%3d&risl=&pid=ImgRaw&r=0') no-repeat center center/cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
            margin: 0;
        }

        .content {
            display: flex;
            justify-content: space-around;
            padding: 20px;
        }

        .card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            width: 30%;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .card h2 {
            color: #007bff;
        }

        .about, .services {
            padding: 20px;
            text-align: center;
        }

        .about h2, .services h2 {
            margin: 0 0 20px;
            color: #007bff;
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

        .footer-links, .social-media {
            margin: 10px 0;
        }

        .footer-links a, .social-media a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Web Hosting Canada</h1>
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

    <section class="hero">
        <p><h1>Your Trusted Web Hosting Partner</h1></p>
        <p><h2>Reliable and Affordable Hosting Solutions</h2></p>
    </section>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>At Web Hosting Canada, we provide top-notch hosting services tailored for businesses of all sizes. Our team is dedicated to ensuring your website runs smoothly and efficiently.</p>
    </section>

    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="content">
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
        </div>
    </section>

    <section id="plans" class="services">
        <h2>Hosting Plans</h2>
        <div class="content">
            <div class="card">
                <h2>Basic Plan</h2>
                <p>Price: <strong>$5/month</strong></p>
                <p>Ideal for personal websites and blogs.</p>
            </div>
            <div class="card">
                <h2>Standard Plan</h2>
                <p>Price: <strong>$10/month</strong></p>
                <p>Perfect for small businesses with moderate traffic.</p>
            </div>
            <div class="card">
                <h2>Premium Plan</h2>
                <p>Price: <strong>$20/month</strong></p>
                <p>Best for high-traffic websites requiring superior performance.</p>
            </div>
        </div>
    </section>

    <footer>
        <div class="footer-links">
            <a href="#">Privacy Policy</a>
            <a href="#">Terms of Service</a>
        </div>
        <div>
           <a href="https://www.facebook.com/WHC.CA"><i class="fab fa-facebook"></i></a>
           <a href="https://twitter.com/webhostcanada"><i class="fab fa-twitter"></i></a>
           <a href="https://www.instagram.com/whc.ca/"><i class="fab fa-instagram"></i></a>

        </div>
        <p>&copy; 2023 Web Hosting Canada. All rights reserved.</p>
        <p> Ayesha Fatima - 301452624 | COMP213 - Individual Project</p>
    </footer>

</body>
</html>
