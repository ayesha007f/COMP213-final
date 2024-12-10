<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - Web Hosting Company</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS for styling -->
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <img src="logo.png" alt="Website Logo" width="150"> <!-- Logo of the website -->
        </div>
        
        <!-- Navigation Bar -->
        <nav>
            <ul>
                <li><a href="registration.html">Create an Account</a></li> <!-- Link to registration page -->
                <li><a href="login.html">Sign In</a></li> <!-- Link to login page -->
                <li><a href="cwh.html">Canadian Web Hosting</a></li> <!-- Link to Canadian Web Hosting page -->
            </ul>
        </nav>
    </header>

    <!-- Search Section -->
    <section class="search-section">
        <h2>Find Your Perfect Hosting Plan</h2>
        <form action="search_results.html" method="GET"> <!-- Form for search functionality -->
            <input type="text" placeholder="Search for hosting plans..." name="query" required>
            <button type="submit">Search</button>
        </form>
    </section>

    <!-- Optional Footer Section -->
    <footer>
        <p>&copy; 2023 Web Hosting Company. All rights reserved.</p>
    </footer>
</body>
</html>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #0056b3;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.search-section {
    padding: 20px;
    text-align: center;
    background-color: #f9f9f9;
}

.search-section form {
    display: inline-block;
}

.search-section input {
    padding: 10px;
    font-size: 16px;
}

.search-section button {
    padding: 10px 20px;
    font-size: 16px;
    background-color: #28a745;
    color: white;
    border: none;
    cursor: pointer;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #0056b3;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}
