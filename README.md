<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Brand - Modern French Vintage Beauty</title>
    <style>
        /* Basic layout styles for a Huda Beauty-inspired site */
        body {
            font-family: 'Arial', sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background: url('your-banner-image.jpg') no-repeat center center / cover;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            text-transform: uppercase;
        }

        .navbar {
            display: flex;
            justify-content: center;
            background-color: #000;
            padding: 1rem;
        }

        .navbar a {
            color: #fff;
            margin: 0 1.5rem;
            text-decoration: none;
            font-size: 1rem;
        }

        .content-section {
            padding: 2rem;
            max-width: 1200px;
            margin: auto;
        }

        .featured-products, .courses, .about-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <!-- Header / Hero Section -->
    <header>
        <h1>Discover Your Beauty</h1>
    </header>

    <!-- Navigation Bar -->
    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#shop">Shop</a>
        <a href="#courses">Courses</a>
        <a href="#contact">Contact</a>
    </div>

    <!-- Content Sections -->
    <section id="home" class="content-section">
        <h2>Featured Products</h2>
        <div class="featured-products">
            <!-- Product Grid Placeholder -->
        </div>
    </section>

    <section id="courses" class="content-section">
        <h2>Courses</h2>
        <div class="courses">
            <!-- Courses Grid Placeholder -->
        </div>
    </section>

    <section id="about" class="content-section about-section">
        <h2>About Us</h2>
        <p>A brief story about your brand, what sets you apart, and your vision.</p>
    </section>

    <!-- Footer -->
    <footer class="footer">
        &copy; 2024 Your Brand Name
    </footer>
</body>
</html>
