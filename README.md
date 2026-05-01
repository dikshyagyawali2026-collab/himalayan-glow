<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Himalayan Herbal Care | Nepal</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&family=Playfair+Display:wght@500&display=swap" rel="stylesheet">

<style>

*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}

body{
background:linear-gradient(135deg,#e8f5e9,#fff7e6);
color:#1b4332;
line-height:1.6;
}

/* NAV */
.navbar{
display:flex;
justify-content:space-between;
padding:18px 50px;
background:rgba(255,255,255,0.85);
backdrop-filter:blur(12px);
position:sticky;
top:0;
z-index:10;
box-shadow:0 2px 10px rgba(0,0,0,0.08);
}

.navbar h2{
font-family:'Playfair Display',serif;
color:#2d6a4f;
}

.navbar a{
margin-left:20px;
text-decoration:none;
color:#2f3e2f;
font-weight:500;
}

.navbar a:hover{
color:#2d6a4f;
}

/* HERO */
.hero{
height:92vh;
background:url('https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
position:relative;
}

.hero::after{
content:'';
position:absolute;
top:0;left:0;
width:100%;
height:100%;
background:rgba(0,0,0,0.5);
}

.hero-content{
position:relative;
max-width:800px;
padding:20px;
}

.hero h1{
font-size:48px;
font-family:'Playfair Display',serif;
}

.hero p{
margin-top:10px;
font-size:16px;
opacity:0.95;
}

/* STORY */
.story{
padding:70px 50px;
max-width:900px;
margin:auto;
text-align:center;
}

.story h2{
font-family:'Playfair Display',serif;
font-size:30px;
margin-bottom:20px;
}

.story p{
font-size:16px;
color:#2f4f2f;
}

/* TITLE */
.section-title{
text-align:center;
font-size:32px;
margin-top:40px;
font-family:'Playfair Display',serif;
}

/* PRODUCTS */
.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:25px;
padding:50px;
max-width:1200px;
margin:auto;
}

/* CARD */
.product{
background:white;
border-radius:16px;
overflow:hidden;
box-shadow:0 10px 25px rgba(0,0,0,0.1);
transition:0.3s;
}

.product:hover{
transform:translateY(-10px);
}

.product img{
width:100%;
height:240px;
object-fit:cover;
}

.product h3{
margin-top:10px;
padding:0 12px;
}

.product p{
color:#2d6a4f;
font-weight:bold;
padding:0 12px 15px;
}

/* CONTACT */
.contact{
background:#1b4332;
color:white;
text-align:center;
padding:60px 20px;
}

.contact p{
margin:6px 0;
}

/* FOOTER */
footer{
background:#081c15;
color:white;
text-align:center;
padding:15px;
font-size:14px;
}

</style>
</head>

<body>

<!-- NAV -->
<div class="navbar">
<h2>Himalayan Herbal</h2>
<div>
<a href="#">Home</a>
<a href="#story">Story</a>
<a href="#products">Products</a>
<a href="#contact">Contact</a>
</div>
</div>

<!-- HERO -->
<div class="hero">
<div class="hero-content">
<h1>Glow Naturally with Himalayan Herbal</h1>
<p>Pure skincare inspired by nature, crafted in Nepal 🇳🇵</p>
</div>
</div>

<!-- STORY -->
<div class="story" id="story">
<h2>Our Story</h2>
<p>
Himalayan Herbal Care was created with a simple vision — to bring the purity of the Himalayas into everyday skincare.
Our journey began in Nepal, where ancient herbal traditions meet modern science.
We carefully select natural ingredients like neem, aloe vera, turmeric, and Himalayan herbs to create safe, effective, and chemical-free skincare products.
<br><br>
Every bottle you see is not just a product — it is a reflection of nature, care, and trust.
We believe beauty should never harm your skin or the environment.
That is why our products are cruelty-free, eco-friendly, and made with love in Nepal.
</p>
</div>

<!-- PRODUCTS -->
<h2 class="section-title">Our Herbal Collection</h2>

<div class="products" id="products">

<div class="product">
<img src="https://images.unsplash.com/photo-1611930021592-a8cfd5319ceb?auto=format&fit=crop&w=800&q=80">
<h3>Face Wash</h3>
<p>Rs 399</p>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1629198735660-e39ea93f5f5d?auto=format&fit=crop&w=800&q=80">
<h3>Vitamin C Serum</h3>
<p>Rs 799</p>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1612810436541-336d3b1c8b6b?auto=format&fit=crop&w=800&q=80">
<h3>Moisturizer</h3>
<p>Rs 599</p>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1616401784845-180882ba9ba3?auto=format&fit=crop&w=800&q=80">
<h3>Herbal Shampoo</h3>
<p>Rs 699</p>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1604908554025-91c4a8f1b1f5?auto=format&fit=crop&w=800&q=80">
<h3>Organic Soap</h3>
<p>Rs 199</p>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1615634260167-c8cdede054de?auto=format&fit=crop&w=800&q=80">
<h3>Natural Perfume</h3>
<p>Rs 999</p>
</div>

</div>

<!-- CONTACT -->
<div class="contact" id="contact">
<h2>Contact Us</h2>
<p>Email: contact@himalayanherbal.com</p>
<p>Phone: 9847000007</p>
<p>Kathmandu, Nepal</p>
</div>

<!-- FOOTER -->
<footer>
<p>Made with ❤️ in Nepal 🇳🇵</p>
</footer>

</body>
</html>
