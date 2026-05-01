<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Himalayan Herbal Care | Nepal</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>

/* RESET */
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#f4f7f3;
color:#2e3d2f;
line-height:1.6;
}

/* HEADER */
header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 60px;
background:#1f3d2b;
color:white;
}

header h1{
font-family:'Playfair Display',serif;
letter-spacing:2px;
}

nav a{
margin-left:25px;
text-decoration:none;
color:white;
font-size:14px;
}

nav a:hover{
color:#c8e6c9;
}

/* HERO */
.hero{
height:90vh;
background:url('https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=1600&q=80') center/cover;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
}

.hero h2{
font-size:50px;
background:rgba(0,0,0,0.45);
padding:25px;
border-radius:10px;
}

/* SECTION */
.section{
padding:70px 60px;
}

.section h2{
text-align:center;
margin-bottom:40px;
font-family:'Playfair Display',serif;
}

/* PRODUCTS */
.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.card{
background:white;
border-radius:12px;
overflow:hidden;
box-shadow:0 6px 15px rgba(0,0,0,0.1);
transition:0.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
height:260px;
object-fit:cover;
}

.card-content{
padding:15px;
}

.card-content h3{
margin-bottom:10px;
font-size:18px;
}

/* ABOUT */
.about{
background:#e8f5e9;
text-align:center;
}

/* CONTACT */
.contact{
background:#1f3d2b;
color:white;
}

.contact form{
max-width:600px;
margin:auto;
display:flex;
flex-direction:column;
}

.contact input, .contact textarea{
margin-bottom:15px;
padding:12px;
border:none;
border-radius:6px;
}

.contact button{
padding:12px;
background:#66bb6a;
border:none;
cursor:pointer;
color:white;
font-weight:bold;
border-radius:6px;
}

/* FOOTER */
footer{
background:#10251a;
color:white;
text-align:center;
padding:20px;
font-size:14px;
}

</style>
</head>

<body>

<!-- HEADER -->
<header>
<h1>Himalayan Herbal</h1>

<nav>
<a href="#">Home</a>
<a href="#products">Products</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>
</header>

<!-- HERO -->
<section class="hero">
<h2>Pure Herbal Beauty from Nepal</h2>
</section>

<!-- PRODUCTS -->
<section class="section" id="products">
<h2>Our Herbal Collection</h2>

<div class="products">

<!-- Aloe Vera Cream -->
<div class="card">
<img src="https://images.unsplash.com/photo-1625772299848-391b6a87d0f2?auto=format&fit=crop&w=800&q=80" alt="Aloe Vera Cream">
<div class="card-content">
<h3>Aloe Vera Face Cream</h3>
<p>Deep hydration with soothing aloe extracts.</p>
</div>
</div>

<!-- Neem Face Wash -->
<div class="card">
<img src="https://images.unsplash.com/photo-1588776814546-1ffcf47267a5?auto=format&fit=crop&w=800&q=80" alt="Face Wash">
<div class="card-content">
<h3>Neem Face Wash</h3>
<p>Herbal cleanser for clear, acne-free skin.</p>
</div>
</div>

<!-- Vitamin C Serum (Dropper Style) -->
<div class="card">
<img src="https://images.unsplash.com/photo-1608248597279-f99d160bfcbc?auto=format&fit=crop&w=800&q=80" alt="Serum Bottle">
<div class="card-content">
<h3>Vitamin C Serum</h3>
<p>Dropper-based serum for glowing, radiant skin.</p>
</div>
</div>

<!-- Body Lotion -->
<div class="card">
<img src="https://images.unsplash.com/photo-1611930022073-b7a4ba5fcccd?auto=format&fit=crop&w=800&q=80" alt="Lotion">
<div class="card-content">
<h3>Herbal Body Lotion</h3>
<p>Soft, nourished skin with natural oils.</p>
</div>
</div>

<!-- Beard Oil -->
<div class="card">
<img src="https://images.unsplash.com/photo-1621605815971-fbc98d665033?auto=format&fit=crop&w=800&q=80" alt="Beard Oil">
<div class="card-content">
<h3>Beard Oil</h3>
<p>Premium grooming oil for men.</p>
</div>
</div>

<!-- Perfume -->
<div class="card">
<img src="https://images.unsplash.com/photo-1615634260167-c8cdede054de?auto=format&fit=crop&w=800&q=80" alt="Perfume">
<div class="card-content">
<h3>Herbal Perfume</h3>
<p>Natural fragrance inspired by Himalayan herbs.</p>
</div>
</div>

</div>
</section>

<!-- ABOUT -->
<section class="section about" id="about">
<h2>About Us</h2>
<p>
Himalayan Herbal is a Nepal-based skincare and grooming brand focused on
natural, eco-friendly, and herbal products. We combine traditional Himalayan
ingredients with modern skincare science.
</p>
</section>

<!-- CONTACT -->
<section class="section contact" id="contact">
<h2>Contact Us</h2>

<form>
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea rows="5" placeholder="Your Message"></textarea>
<button type="submit">Send Message</button>
</form>

<p style="text-align:center; margin-top:20px;">
📧 Email: contact@himalayanherbal.com <br>
📞 Contact: 9847000007 <br>
📍 Kathmandu, Nepal
</p>

</section>

<!-- FOOTER -->
<footer>
<p>© 2026 Himalayan Herbal | Made with ❤️ in Nepal 🇳🇵</p>
</footer>

</body>
</html>
