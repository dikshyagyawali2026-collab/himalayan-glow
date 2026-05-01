# himalayan-glow<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Himalayan Glow - Nepal Cosmetics</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background-color: #fff;
            color: #333;
        }

        header {
            background: #111;
            color: white;
            padding: 20px 60px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 24px;
            letter-spacing: 2px;
        }

        nav a {
            color: white;
            margin-left: 25px;
            text-decoration: none;
            font-size: 14px;
        }

        nav a:hover {
            color: #f8c291;
        }

        .hero {
            height: 90vh;
            background: url('https://images.unsplash.com/photo-1600185365483-26d7a4cc7519') center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }

        .hero h2 {
            font-size: 48px;
            background: rgba(0,0,0,0.5);
            padding: 20px;
        }

        .section {
            padding: 60px;
        }

        .section h2 {
            text-align: center;
            margin-bottom: 40px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .card {
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
            transition: 0.3s;
            background: #fff;
        }

        .card:hover {
            transform: translateY(-8px);
        }

        .card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .card-content {
            padding: 15px;
        }

        .card-content h3 {
            margin-bottom: 10px;
        }

        .about {
            background: #f9f9f9;
            text-align: center;
        }

        .contact {
            background: #111;
            color: white;
        }

        .contact form {
            max-width: 600px;
            margin: auto;
            display: flex;
            flex-direction: column;
        }

        .contact input, .contact textarea {
            margin-bottom: 15px;
            padding: 10px;
            border: none;
        }

        .contact button {
            padding: 12px;
            background: #f8c291;
            border: none;
            cursor: pointer;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #000;
            color: white;
        }
    </style>
</head>

<body>

<!-- HEADER -->
<header>
    <h1>Himalayan Glow</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- HERO -->
<section class="hero">
    <h2>Natural Beauty from Nepal</h2>
</section>

<!-- PRODUCTS -->
<section class="section" id="products">
    <h2>Our Products</h2>

    <div class="products">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1596462502278-27bfdc403348">
            <div class="card-content">
                <h3>Organic Face Cream</h3>
                <p>Hydrates and nourishes skin naturally.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1620912189860-5a2a0c5e8f33">
            <div class="card-content">
                <h3>Herbal Face Wash</h3>
                <p>Gentle cleansing with Himalayan herbs.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1585386959984-a4155224a1ad">
            <div class="card-content">
                <h3>Beard Grooming Kit</h3>
                <p>Complete grooming essentials for men.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1608248597279-f99d160bfcbc">
            <div class="card-content">
                <h3>Body Lotion</h3>
                <p>Soft and smooth skin all day long.</p>
            </div>
        </div>

    </div>
</section>

<!-- ABOUT -->
<section class="section about" id="about">
    <h2>About Us</h2>
    <p>
        Himalayan Glow is a Nepal-based cosmetic brand dedicated to natural skincare,
        grooming, and self-care products. We use locally sourced ingredients from the
        Himalayas to ensure purity and quality.
    </p>
</section>

<!-- CONTACT -->
<section class="section contact" id="contact">
    <h2>Contact Us</h2>

    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea rows="5" placeholder="Message"></textarea>
        <button type="submit">Send Message</button>
    </form>

    <p style="text-align:center; margin-top:20px;">
        Email: support@himalayanglow.com <br>
        Location: Kathmandu, Nepal
    </p>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 Himalayan Glow | All Rights Reserved</p>
</footer>

</body>
</html>
