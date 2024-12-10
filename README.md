
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Project</title>
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
            background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
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

        footer {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Sample Project</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to Our Website</h1>
    </section>

    <section class="content">
        <div class="card">
            <h2>About Us</h2>
            <p>We provide high-quality services to our clients.</p>
        </div>
        <div class="card">
            <h2>Our Services</h2>
            <p>Check out our wide range of services tailored to your needs.</p>
        </div>
        <div class="card">
            <h2>Contact Us</h2>
            <p>Get in touch with us for more information.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Sample Project. All rights reserved.</p>
    </footer>

</body>
</html>
