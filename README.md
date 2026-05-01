
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Himalayan Herbal</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">

<style>

*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}

body{background:#f9f9f9;}

/* NAVBAR */
.navbar{
display:flex;
justify-content:space-between;
padding:20px 50px;
background:white;
box-shadow:0 2px 5px rgba(0,0,0,0.1);
position:sticky;
top:0;
}

.navbar h2{color:#2d6a4f;}

.navbar a{
margin-left:20px;
text-decoration:none;
color:#333;
}

/* HERO */
.hero{
height:80vh;
background:url('https://images.pexels.com/photos/6621461/pexels-photo-6621461.jpeg') center/cover;
display:flex;
align-items:center;
justify-content:center;
color:white;
text-align:center;
}

.hero h1{
background:rgba(0,0,0,0.5);
padding:20px;
}

/* SECTION */
.section{
padding:60px 40px;
text-align:center;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
margin-top:30px;
}

.product{
background:white;
padding:15px;
border-radius:10px;
box-shadow:0 3px 8px rgba(0,0,0,0.1);
}

.product img{
width:100%;
height:200px;
object-fit:cover;
border-radius:10px;
}

.price{
color:green;
font-weight:bold;
margin-top:5px;
}

/* CONTACT */
.contact{
background:#2d6a4f;
color:white;
padding:50px;
text-align:center;
}

/* FOOTER */
footer{
background:#111;
color:white;
text-align:center;
padding:15px;
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

<!-- HERO -->
<div class="hero">
<h1>Natural Skincare from Nepal</h1>
</div>

<!-- PRODUCTS -->
<div class="section" id="products">
<h2>Our Products</h2>

<div class="products">

<div class="product">
<img src="https://images.pexels.com/photos/4041392/pexels-photo-4041392.jpeg">
<h3>Face Wash</h3>
<p>Rs 399</p>
</div>

<div class="product">
<img src="https://images.pexels.com/photos/4465124/pexels-photo-4465124.jpeg">
<h3>Serum</h3>
<p>Rs 799</p>
</div>

<div class="product">
<img src="https://images.pexels.com/photos/6621460/pexels-photo-6621460.jpeg">
<h3>Moisturizer</h3>
<p>Rs 599</p>
</div>

<div class="product">
<img src="https://images.pexels.com/photos/3738347/pexels-photo-3738347.jpeg">
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
