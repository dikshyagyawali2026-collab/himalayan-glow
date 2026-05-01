<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Himalayan Herbal | Nepal</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}

body{background:#f4f7f3;color:#2e3d2f;}

header{
display:flex;
justify-content:space-between;
padding:20px 50px;
background:#1f3d2b;
color:white;
}

nav a{
margin-left:20px;
color:white;
text-decoration:none;
}

.hero{
height:80vh;
background:url('https://images.pexels.com/photos/6621461/pexels-photo-6621461.jpeg') center/cover;
display:flex;
align-items:center;
justify-content:center;
color:white;
}

.hero h1{
background:rgba(0,0,0,0.5);
padding:20px;
border-radius:10px;
}

.section{padding:60px;}

.section h2{text-align:center;margin-bottom:30px;}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:10px;
overflow:hidden;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
transition:0.3s;
}

.card:hover{transform:translateY(-8px);}

.card img{
width:100%;
height:250px;
object-fit:cover;
}

.card-content{padding:15px;}

.price{
color:#1b5e20;
font-weight:bold;
margin-top:8px;
}

/* CONTACT */
.contact{background:#1f3d2b;color:white;}

.contact form{
max-width:500px;
margin:auto;
display:flex;
flex-direction:column;
}

.contact input,.contact textarea{
margin-bottom:10px;
padding:10px;
border:none;
border-radius:5px;
}

.contact button{
padding:10px;
background:#66bb6a;
border:none;
color:white;
cursor:pointer;
}

/* FOOTER */
footer{
background:#000;
color:white;
text-align:center;
padding:20px;
}
</style>
</head>

<body>

<header>
<h2>Himalayan Herbal</h2>
<nav>
<a href="#">Home</a>
<a href="#products">Products</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero">
<h1>Pure Herbal Skincare from Nepal</h1>
</section>

<section class="section" id="products">
<h2>Our Products</h2>

<div class="products">

<div class="card">
<img src="https://images.pexels.com/photos/4041392/pexels-photo-4041392.jpeg">
<div class="card-content">
<h3>Herbal Face Wash</h3>
<p>Gentle neem & tulsi cleanser</p>
<p class="price">Rs 399</p>
</div>
</div>

<div class="card">
<img src="https://images.pexels.com/photos/4465124/pexels-photo-4465124.jpeg">
<div class="card-content">
<h3>Vitamin C Serum</h3>
<p>Brightening glow serum</p>
<p class="price">Rs 799</p>
</div>
</div>

<div class="card">
<img src="https://images.pexels.com/photos/6621460/pexels-photo-6621460.jpeg">
<div class="card-content">
<h3>Herbal Moisturizer</h3>
<p>Deep hydration cream</p>
<p class="price">Rs 599</p>
</div>
</div>

<div class="card">
<img src="https://images.pexels.com/photos/3738347/pexels-photo-3738347.jpeg">
<div class="card-content">
<h3>Herbal Shampoo</h3>
<p>Hair strengthening formula</p>
<p class="price">Rs 699</p>
</div>
</div>

<div class="card">
<img src="https://images.pexels.com/photos/6621338/pexels-photo-6621338.jpeg">
<div class="card-content">
<h3>Organic Soap</h3>
<p>Handmade essential oil soap</p>
<p class="price">Rs 199</p>
</div>
</div>

<div class="card">
<img src="https://images.pexels.com/photos/6621463/pexels-photo-6621463.jpeg">
<div class="card-content">
<h3>Herbal Hair Oil</h3>
<p>Strong & healthy hair care</p>
<p class="price">Rs 499</p>
</div>
</div>

</div>
</section>

<section class="section contact" id="contact">
<h2>Contact Us</h2>

<form>
<input type="text" placeholder="Your Name">
<input type="email" placeholder="Your Email">
<textarea placeholder="Message"></textarea>
<button>Send Message</button>
</form>

<p style="text-align:center;margin-top:15px;">
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
