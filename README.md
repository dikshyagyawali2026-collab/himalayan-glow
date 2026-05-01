<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Himalayan Herbal Care | Nepal</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&family=Playfair+Display:wght@500&display=swap" rel="stylesheet">

<style>

*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}

body{
background:linear-gradient(135deg,#e8f5e9,#fefae0);
color:#1b4332;
}

/* NAV */
.navbar{
display:flex;
justify-content:space-between;
padding:18px 50px;
background:rgba(255,255,255,0.8);
backdrop-filter:blur(10px);
position:sticky;
top:0;
z-index:10;
}

.navbar h2{
font-family:'Playfair Display',serif;
color:#2d6a4f;
}

.navbar a{
margin-left:20px;
text-decoration:none;
color:#333;
}

/* HERO */
.hero{
height:90vh;
background:url('https://images.unsplash.com/photo-1611930022073-b7a4ba5fcccd?auto=format&fit=crop&w=1600&q=80') center/cover;
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
background:rgba(0,0,0,0.45);
}

.hero-content{
position:relative;
}

.hero h1{
font-size:44px;
font-family:'Playfair Display',serif;
}

.hero p{
margin-top:10px;
}

/* PRODUCTS */
.section-title{
text-align:center;
font-size:30px;
margin:50px 0 20px;
font-family:'Playfair Display',serif;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
gap:25px;
padding:40px;
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
height:240px;
object-fit:cover;
}

.product h3{
margin-top:10px;
padding-left:10px;
}

.product p{
color:#2d6a4f;
font-weight:bold;
padding-left:10px;
padding-bottom:15px;
}

/* CONTACT */
.contact{
background:#1b4332;
color:white;
text-align:center;
padding:60px 20px;
}

/* FOOTER */
footer{
background:#081c15;
color:white;
text-align:center;
padding:15px;
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
<div class="hero-content">
<h1>Glow Naturally with Herbal Skincare</h1>
<p>Pure Himalayan beauty in every bottle</p>
</div>
</div>

<!-- PRODUCTS -->
<h2 class="section-title">Our Herbal Bottles & Tubes</h2>

<div class="products" id="products">

<!-- FACEWASH BOTTLE -->
<div class="product">
<img src="https://images.unsplash.com/photo-1620916566398-39f1143ab7be?auto=format&fit=crop&w=800&q=80">
<h3>Herbal Face Wash</h3>
<p>Rs 399</p>
</div>

<!-- SERUM DROPPER BOTTLE -->
<div class="product">
<img src="https://images.unsplash.com/photo-1611930021592-a8cfd5319ceb?auto=format&fit=crop&w=800&q=80">
<h3>Vitamin C Serum</h3>
<p>Rs 799</p>
</div>

<!-- MOISTURIZER TUBE -->
<div class="product">
<img src="https://images.unsplash.com/photo-1629198735660-e39ea93f5f5d?auto=format&fit=crop&w=800&q=80">
<h3>Moisturizer Cream</h3>
<p>Rs 599</p>
</div>

<!-- SHAMPOO BOTTLE -->
<div class="product">
<img src="https://images.unsplash.com/photo-1616401784845-180882ba9ba3?auto=format&fit=crop&w=800&q=80">
<h3>Herbal Shampoo</h3>
<p>Rs 699</p>
</div>

<!-- SOAP BAR -->
<div class="product">
<img src="https://images.unsplash.com/photo-1604908554025-91c4a8f1b1f5?auto=format&fit=crop&w=800&q=80">
<h3>Organic Soap</h3>
<p>Rs 199</p>
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
