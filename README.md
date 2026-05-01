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
background:#f5f8f5;
color:#2f3e2f;
}

/* HEADER */
header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 60px;
background:#1b4332;
color:white;
}

header h1{
font-family:'Playfair Display',serif;
}

nav a{
margin-left:25px;
text-decoration:none;
color:white;
}

nav a:hover{
color:#a7c957;
}

/* HERO */
.hero{
height:85vh;
background:url('https://images.unsplash.com/photo-1598440947619-2c35fc9aa908?auto=format&fit=crop&w=1600&q=80') center/cover;
display:flex;
align-items:center;
justify-content:center;
color:white;
text-align:center;
}

.hero h2{
font-size:48px;
background:rgba(0,0,0,0.4);
padding:20px;
border-radius:10px;
}

/* SECTION */
.section{
padding:60px;
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
box-shadow:0 5px 15px rgba(0,0,0,0.1);
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
}

/* ABOUT */
.about{
background:#e9f5ec;
text-align:center;
}

/* CONTACT */
.contact{
background:#1b4332;
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
background:#52b788;
border:none;
color:white;
font-weight:bold;
cursor:pointer;
}

/* FOOTER */
footer{
background:#081c15;
color:white;
text-align:center;
padding:20px;
}

</style>
</head>

<body>

<header>
<h1>Himalayan Herbal</h1>
<nav>
<a href="#">Home</a>
<a href="#products">Products</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero">
<h2>Nature’s Touch for Your Skin & Hair</h2>
</section>

<section class="section" id="products">
<h2>Our Herbal Collection</h2>

<div class="products">

<!-- Face Wash -->
<div class="card">
<img src="https://images.unsplash.com/photo-1585238342028-78d387f4a707?auto=format&fit=crop&w=800&q=80" alt="Face Wash">
<div class="card-content">
<h3>Herbal Face Wash</h3>
<p>Gentle daily cleanser with neem and tulsi.</p>
</div>
</div>

<!-- Serum -->
<div class="card">
<img src="https://images.unsplash.com/photo-1629198735660-e39ea93f5f5d?auto=format&fit=crop&w=800&q=80" alt="Serum">
<div class="card-content">
<h3>Vitamin C Serum</h3>
<p>Dropper-based serum for radiant glowing skin.</p>
</div>
</div>

<!-- Moisturizer -->
<div class="card">
<img src="https://images.unsplash.com/photo-1611930021592-a8cfd5319ceb?auto=format&fit=crop&w=800&q=80" alt="Moisturizer">
<div class="card-content">
<h3>Herbal Moisturizer</h3>
<p>Deep hydration with natural plant extracts.</p>
</div>
</div>

<!-- Shampoo -->
<div class="card">
<img src="https://images.unsplash.com/photo-1600185365483-26d7a4cc7519?auto=format&fit=crop&w=800&q=80" alt="Shampoo">
<div class="card-content">
<h3>Herbal Shampoo</h3>
<p>Strengthens hair and reduces hair fall.</p>
</div>
</div>

<!-- Soap -->
<div class="card">
<img src="https://images.unsplash.com/photo-1604908554025-91c4a8f1b1f5?auto=format&fit=crop&w=800&q=80" alt="Soap">
<div class="card-content">
<h3>Organic Soap</h3>
<p>Handmade soap with essential oils.</p>
</div>
</div>

<!-- Hair Oil -->
<div class="card">
<img src="https://images.unsplash.com/photo-1621605815971-fbc98d665033?auto=format&fit=crop&w=800&q=80" alt="Hair Oil">
<div class="card-content">
<h3>Herbal Hair Oil</h3>
<p>Promotes healthy and shiny hair.</p>
</div>
</div>

</div>
</section>

<section class="section about" id="about">
<h2>About Us</h2>
<p>
Himalayan Herbal is a Nepal-based brand creating natural skincare,
haircare, and grooming products using Himalayan herbs.
</p>
</section>

<section class="section contact" id="contact">
<h2>Contact Us</h2>

<form>
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea rows="5" placeholder="Message"></textarea>
<button type="submit">Send Message</button>
</form>

<p style="text-align:center; margin-top:20px;">
📧 contact@himalayanherbal.com <br>
📞 9847000007 <br>
📍 Kathmandu, Nepal
</p>

</section>

<footer>
<p>© 2026 Himalayan Herbal | Made with ❤️ in Nepal 🇳🇵</p>
</footer>

</body>
</html>
