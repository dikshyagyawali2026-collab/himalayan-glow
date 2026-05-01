<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Himalayan Herbal Care</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>

/* RESET */
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:linear-gradient(135deg,#e8f5e9,#f1f8e9);
color:#1b4332;
}

/* GLASS NAVBAR */
.navbar{
display:flex;
justify-content:space-between;
align-items:center;
padding:18px 50px;
background:rgba(255,255,255,0.6);
backdrop-filter:blur(10px);
position:sticky;
top:0;
box-shadow:0 2px 10px rgba(0,0,0,0.08);
}

.navbar h2{
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
height:85vh;
background:url('https://images.unsplash.com/photo-1612810436541-336d3b1c8b6b?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
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
background:rgba(0,0,0,0.35);
}

.hero h1{
position:relative;
font-size:42px;
background:rgba(0,0,0,0.4);
padding:20px 30px;
border-radius:12px;
}

/* SECTION */
.section{
padding:70px 40px;
text-align:center;
}

.section h2{
margin-bottom:30px;
font-size:28px;
}

/* PRODUCTS GRID */
.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
gap:25px;
max-width:1100px;
margin:auto;
}

/* CARD */
.product{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 8px 20px rgba(0,0,0,0.08);
transition:0.3s;
}

.product:hover{
transform:translateY(-8px);
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
margin:8px 0;
}

/* FOOTER */
footer{
background:#0b1d13;
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
<a href="#products">Products</a>
<a href="#contact">Contact</a>
</div>
</div>

<!-- HERO -->
<div class="hero">
<h1>Pure Herbal Skincare from Nepal 🌿</h1>
</div>

<!-- PRODUCTS -->
<div class="section" id="products">
<h2>Our Herbal Collection</h2>

<div class="products">

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
