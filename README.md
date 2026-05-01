<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Himalayan Herbal Care | Story of Nature & Skin</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&family=Playfair+Display:wght@500&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:linear-gradient(135deg,#e8f5e9,#fefae0);
color:#1b4332;
}

/* NAVBAR */
.navbar{
display:flex;
justify-content:space-between;
align-items:center;
padding:18px 50px;
background:rgba(255,255,255,0.7);
backdrop-filter:blur(12px);
position:sticky;
top:0;
z-index:10;
box-shadow:0 3px 10px rgba(0,0,0,0.08);
}

.navbar h2{
color:#2d6a4f;
font-family:'Playfair Display',serif;
}

.navbar a{
margin-left:20px;
text-decoration:none;
color:#2f3e2f;
font-weight:500;
}

/* HERO */
.hero{
height:90vh;
background:url('https://images.unsplash.com/photo-1612810436541-336d3b1c8b6b?auto=format&fit=crop&w=1600&q=80') center/cover;
display:flex;
align-items:center;
justify-content:center;
position:relative;
text-align:center;
color:white;
}

.hero::after{
content:'';
position:absolute;
top:0;left:0;
width:100%;
height:100%;
background:rgba(0,0,0,0.45);
}

.hero-content{
position:relative;
max-width:800px;
}

.hero h1{
font-size:44px;
font-family:'Playfair Display',serif;
margin-bottom:10px;
}

.hero p{
font-size:16px;
}

/* STORY */
.story{
padding:70px 40px;
text-align:center;
max-width:900px;
margin:auto;
}

.story h2{
font-family:'Playfair Display',serif;
margin-bottom:20px;
}

.story p{
line-height:1.7;
color:#3a5a40;
}

/* PRODUCTS */
.section-title{
text-align:center;
margin-top:40px;
font-size:28px;
font-family:'Playfair Display',serif;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
padding:50px 40px;
max-width:1200px;
margin:auto;
}

/* CARD */
.product{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 8px 20px rgba(0,0,0,0.1);
transition:0.3s;
}

.product:hover{
transform:translateY(-10px);
}

.product img{
width:100%;
height:220px;
object-fit:cover;
}

.product h3{
margin-top:10px;
}

.product p{
color:#2d6a4f;
font-weight:bold;
margin-bottom:15px;
}

/* CONTACT */
.contact{
background:#1b4332;
color:white;
padding:60px 20px;
text-align:center;
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

<!-- NAVBAR -->
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
<h1>Nature, Tradition & Beauty from Nepal 🇳🇵</h1>
<p>Herbal skincare crafted from Himalayan ingredients for pure, healthy skin</p>
</div>
</div>

<!-- STORY -->
<div class="story" id="story">
<h2>Our Story</h2>
<p>
Himalayan Herbal was born in the heart of Nepal with a simple belief —
nature already has everything your skin needs.
We combine Himalayan herbs, Ayurvedic wisdom, and modern skincare science
to create products that are pure, safe, and effective.
</p>
</div>

<h2 class="section-title">Our Herbal Collection</h2>

<!-- PRODUCTS -->
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
<img src="https://images.unsplash.com/photo-1608248597279-f99d160bfcbc?auto=format&fit=crop&w=800&q=80">
<h3>Glow Serum</h3>
<p>Rs 899</p>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1616401784845-180882ba9ba3?auto=format&fit=crop&w=800&q=80">
<h3>Herbal Shampoo</h3>
<p>Rs 699</p>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1611930022073-b7a4ba5fcccd?auto=format&fit=crop&w=800&q=80">
<h3>Body Lotion</h3>
<p>Rs 599</p>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1604908554025-91c4a8f1b1f5?auto=format&fit=crop&w=800&q=80">
<h3>Herbal Soap</h3>
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
<p>Location: Kathmandu, Nepal</p>
</div>

<!-- FOOTER -->
<footer>
<p>Made with ❤️ in Nepal 🇳🇵 | Himalayan Herbal Care</p>
</footer>

</body>
</html>
