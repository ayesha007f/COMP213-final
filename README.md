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
        }

        header {
            background: #282c34;
            color: white;
            padding: 1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        .search-section {
            padding: 1rem;
            text-align: center;
        }

        .hero {
            text-align: center;
            margin: 20px 0;
        }

        .plans {
            display: flex;
            justify-content: space-around;
            padding: 20px;
        }

        .plan {
            border: 1px solid #ccc;
            padding: 20px;
            width: 30%;
        }

        footer {
            background: #282c34;
            color: white;
            padding: 1rem;
            text-align: center;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .form-section {
            padding: 20px;
            text-align: center;
        }

        .form-section form {
            display: inline-block;
            text-align: left;
        }

        .form-section label {
            display: block;
            margin: 10px 0 5px;
        }

        .form-section input {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
        }

        .form-section button {
            padding: 10px 20px;
            background: #282c34;
            color: white;
            border: none;
        }
    </style>
</head>
<body>

    <!-- Home Page -->
    <div id="home">
        <header>
            <div class="logo">
                <h1>WHC</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#registration">Sign Up</a></li>
                    <li><a href="#login">Login</a></li>
                </ul>
            </nav>
        </header>

        <section class="search-section">
            <input type="text" placeholder="Search...">
            <button type="submit">Search</button>
        </section>

        <section class="hero">
            <h2>Welcome to Web Hosting Canada</h2>
            <img src="hero-image.jpg" alt="Hero Image" />
        </section>

        <footer>
            <div class="footer-links">
                <a href="#">Privacy Policy</a>
                <a href="#">Terms of Service</a>
            </div>
            <div class="social-media">
                <a href="#">Facebook</a>
                <a href="#">Twitter</a>
                <a href="#">Instagram</a>
            </div>
        </footer>
    </div>

    <!-- Canadian Web Hosting Plans Page -->
    <div id="plans" style="display:none;">
        <header>
            <div class="logo">
                <h1>WHC</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#registration">Sign Up</a></li>
                    <li><a href="#login">Login</a></li>
                </ul>
            </nav>
        </header>

        <section class="hero">
            <h2>Our Hosting Plans</h2>
        </section>

        <section class="plans">
            <div class="plan">
                <h3>Basic Plan</h3>
                <p>Price: $5/month</p>
                <p>Details: Suitable for personal websites.</p>
            </div>
            <div class="plan">
                <h3>Standard Plan</h3>
                <p>Price: $10/month</p>
                <p>Details: Perfect for small businesses.</p>
            </div>
            <div class="plan">
                <h3>Premium Plan</h3>
                <p>Price: $20/month</p>
                <p>Details: Best for high-traffic websites.</p>
            </div>
        </section>

        <footer>
            <div class="footer-links">
                <a href="#">Privacy Policy</a>
                <a href="#">Terms of Service</a>
            </div>
            <div class="social-media">
                <a href="#">Facebook</a>
                <a href="#">Twitter</a>
                <a href="#">Instagram</a>
            </div>
        </footer>
    </div>

    <!-- Registration Page -->
    <div id="registration" style="display:none;">
        <header>
            <div class="logo">
                <h1>WHC</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#registration">Sign Up</a></li>
                    <li><a href="#login">Login</a></li>
                </ul>
            </nav>
        </header>

        <section class="form-section">
            <h2>Create Your Account</h2>
            <form>
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>

                <button type="submit">Register</button>
            </form>
        </section>

        <footer>
            <div class="footer-links">
                <a href="#">Privacy Policy</a>
                <a href="#">Terms of Service</a>
            </div>
            <div class="social-media">
                <a href="#">Facebook</a>
                <a href="#">Twitter</a>
                <a href="#">Instagram</a>
            </div>
        </footer>
    </div>

    <!-- Login Page -->
    <div id="login" style="display:none;">
        <header>
            <div class="logo">
                <h1>WHC</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#registration">Sign Up</a></li>
                    <li><a href="#login">Login</a></li>
                </ul>
            </nav>
        </header>

        <section class="form-section">
            <h2>Login to Your Account</h2>
            <form>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>

                <button type="submit">Login</button>
            </form>
        </section>

        <footer>
            <div class="footer-links">
                <a href="#">Privacy Policy</a>
                <a href="#">Terms of Service</a>
            </div>
            <div class="social-media">
                <a href="#">Facebook</a>
                <a href="#">Twitter</a>
                <a href="#">Instagram</a>
            </div>
        </footer>
    </div>

    <script>
        // Navigation script to switch between pages
        document.querySelectorAll('nav a').forEach(link => {
            link.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelectorAll('div[id]').forEach(div => div.style.display = 'none');
                const target = this.getAttribute('href').substring(1);
                document.getElementById(target).style.display = 'block';
            });
        });

        // Display the home page by default
        document.getElementById('home').style.display = 'block';
    </script>

</body>
</html>
