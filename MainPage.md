<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infinity Builds | No Limits. Just Creations.</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav li {
            margin: 0 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://source.unsplash.com/random/1600x900/?lego,puzzle') center/cover;
            color: white;
        }

        .hero h1 {
            font-size: 3rem;
            margin: 0;
        }

        .section {
            padding: 40px 20px;
            text-align: center;
        }

        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .service-card {
            border: 1px solid #ccc;
            border-radius: 10px;
            margin: 15px;
            padding: 20px;
            width: 300px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <h1>Infinity Builds</h1>
        <p>No Limits. Just Creations.</p>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Welcome to Infinity Builds</h1>
        <p>We build without limits, so you get exactly what you imagined.</p>
        <a href="#contact" style="color: white; text-decoration: underline;">Get Started Now</a>
    </section>

    <section id="services" class="section">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service-card">
                <h3>LEGO Assembly</h3>
                <p>Custom LEGO builds brought to life, brick by brick.</p>
            </div>
            <div class="service-card">
                <h3>Puzzle Making</h3>
                <p>Let us handle complex puzzles so you can enjoy the final masterpiece.</p>
            </div>
            <div class="service-card">
                <h3>Website Building</h3>
                <p>Need a custom website? Our experts build exactly what you need.</p>
            </div>
            <div class="service-card">
                <h3>Script Development</h3>
                <p>Custom scripts and solutions for your projects.</p>
            </div>
        </div>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>Infinity Builds is your one-stop shop for creative builds. From LEGO and puzzles to coding and websites, our mission is to make your vision a reality without limits.</p>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Have a project in mind? Send us a message and let’s build something great together!</p>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Infinity Builds. All Rights Reserved.</p>
    </footer>
</body>

</html>
