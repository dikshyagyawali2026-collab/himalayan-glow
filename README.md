<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Himalayan Herbal Care | Nepal</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&family=Playfair+Display:wght@500&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#f5faf5;
color:#1b4332;
}

/* NAVBAR */
.navbar{
display:flex;
justify-content:space-between;
align-items:center;
padding:18px 50px;
background:rgba(255,255,255,0.75);
backdrop-filter:blur(10px);
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

/* HERO */
.hero{
height:92vh;
background:url('https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
display:flex;
align-items:center;
justify-content:center;
position:relative;
color:white;
text-align:center;
}

/* DARK OVERLAY */
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
padding:20px;
}

.hero h1{
font-size:48px;
font-family:'Playfair Display',serif;
margin-bottom:10px;
}

.hero p{
font-size:16px;
opacity:0.9;
}

/* BUTTON */
.btn{
margin-top:20px;
display:inline-block;
padding:12px 25px;
background:#52b788;
color:white;
text-decoration:none;
border-radius:25px;
font-weight:500;
transition:0.3s;
}

.btn:hover{
background:#2d6a4f;
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

/* PRODUCTS */
.section-title{
text-align:center;
margin-top:40px;
font-size:30px;
font-family:'Playfair Display',serif;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
gap:25px;
padding:50px 40px;
max-width:1200px;
margin:auto;
}

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
<a href="#products">Products</a>
<a href="#contact">Contact</a>
</div>
</div>

<!-- HERO SECTION (FIXED - GIRL AD IMAGE) -->
<div class="hero">
<div class="hero-content">
<h1>Glow Naturally with Himalayan Herbal</h1>
<p>Pure skincare inspired by nature, trusted by women across Nepal</p>
<a href="#products" class="btn">Explore Products</a>
</div>
</div>

<!-- STORY -->
<div class="story">
<h2>Our Story</h2>
<p>
We create herbal skincare using Himalayan ingredients that nourish your skin naturally.
Our goal is simple — pure beauty without chemicals.
</p>
</div>

<!-- PRODUCTS -->
<h2 class="section-title">Best Selling Products</h2>

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
<h3>Shampoo</h3>
<p>Rs 699</p>
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
<p>Made with ❤️ in Nepal 🇳🇵 | Himalayan Herbal Care</p>
</footer>

</body>
</html>
