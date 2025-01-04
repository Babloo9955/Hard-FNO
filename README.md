

HTML
```
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EasyFNO</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li><a href="#">Options Trading</a></li>
                <li><a href="#">Market Data</a></li>
                <li><a href="#">News</a></li>
                <li><a href="#">Login/Register</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Welcome to EasyFNO</h1>
        <p>Your trusted source for options trading analysis and market data.</p>
        <button>Sign Up Now</button>
    </section>

    <!-- Featured Services Section -->
    <section class="featured-services">
        <h2>Our Featured Services</h2>
        <div class="service-card">
            <h3>Options Trading Analysis</h3>
            <p>Get expert analysis and insights on options trading.</p>
        </div>
        <div class="service-card">
            <h3>Market Data</h3>
            <p>Stay up-to-date with real-time market data and charts.</p>
        </div>
    </section>

    <!-- Latest News Section -->
    <section class="latest-news">
        <h2>Latest News</h2>
        <div class="news-card">
            <h3>News Article 1</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <div class="news-card">
            <h3>News Article 2</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2023 EasyFNO. All rights reserved.</p>
    </footer>
</body>
</html>
```

CSS
```
/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4567b7;
    color: #ffffff;
    padding: 20px;
    text-align: center;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

header nav ul li {
    display: inline-block;
    margin-right: 20px;
}

header nav a {
    color: #ffffff;
    text-decoration: none;
}

.hero {
    background-image: url('hero-background.jpg');
    background-size: cover;
    background-position: center;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #ffffff;
}

.featured-services {
    padding: 20px;
}

.service-card {
    background-color: #f7f7f7;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.latest-news {
    padding: 20px;
}

.news-card {
    background-color: #f7f7f7;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #4567b7;
    color: #ffffff;
    padding: 10px;
    text-align: center;
    clear: both;
}
```

JavaScript
```
// script.js
// Add event listener to button
document.querySelector('button').addEventListener('click', function() {
    // Code to handle button click
});
```
