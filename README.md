<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BEATRIX OFFICIAL</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#fff;
    color:#111;
}

/* NAVBAR */

header{
    position:fixed;
    width:100%;
    top:0;
    left:0;
    padding:20px 7%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    background:rgba(255,255,255,0.95);
    backdrop-filter:blur(10px);
    z-index:1000;
    border-bottom:1px solid #eee;
}

.logo{
    font-size:30px;
    font-weight:700;
    letter-spacing:3px;
}

nav{
    display:flex;
    gap:30px;
}

nav a{
    color:#111;
    text-decoration:none;
    font-weight:500;
    transition:0.3s;
}

nav a:hover{
    color:#b48a55;
}

/* HERO */

.hero{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,0.35),rgba(0,0,0,0.35)),
    url('https://images.unsplash.com/photo-1529139574466-a303027c1d8b?q=80&w=1800&auto=format&fit=crop');
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
    padding:20px;
}

.hero-content h1{
    font-size:72px;
    margin-bottom:20px;
    letter-spacing:3px;
}

.hero-content p{
    font-size:20px;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:15px 40px;
    background:#fff;
    color:#111;
    border-radius:50px;
    text-decoration:none;
    font-weight:600;
    transition:0.3s;
}

.btn:hover{
    background:#b48a55;
    color:white;
}

/* SECTION */

section{
    padding:100px 7%;
}

.section-title{
    text-align:center;
    margin-bottom:60px;
}

.section-title h2{
    font-size:42px;
    margin-bottom:10px;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:30px;
}

.card{
    overflow:hidden;
    border-radius:20px;
    background:white;
    box-shadow:0 5px 25px rgba(0,0,0,0.08);
    transition:0.4s;
}

.card:hover{
    transform:translateY(-10px);
}

.card img{
    width:100%;
    height:340px;
    object-fit:cover;
}

.card-content{
    padding:20px;
}

.card-content h3{
    margin-bottom:10px;
    font-size:22px;
}

.price{
    font-size:20px;
    font-weight:700;
    color:#b48a55;
    margin-bottom:15px;
}

.buy-btn{
    width:100%;
    border:none;
    padding:13px;
    border-radius:12px;
    background:#111;
    color:white;
    cursor:pointer;
    transition:0.3s;
}

.buy-btn:hover{
    background:#b48a55;
}

/* BANNER */

.banner{
    height:400px;
    border-radius:30px;
    overflow:hidden;
    background:
    linear-gradient(rgba(0,0,0,0.3),rgba(0,0,0,0.3)),
    url('https://images.unsplash.com/photo-1496747611176-843222e1e57c?q=80&w=1800&auto=format&fit=crop');
    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
    justify-content:center;
    color:white;
    text-align:center;
}

.banner h2{
    font-size:50px;
}

/* FOOTER */

footer{
    background:#111;
    color:white;
    padding:60px 7%;
}

.footer-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:40px;
}

.footer-grid h3{
    margin-bottom:20px;
}

.footer-grid p,
.footer-grid a{
    color:#bbb;
    line-height:2;
    text-decoration:none;
}

.copy{
    text-align:center;
    margin-top:40px;
    border-top:1px solid #333;
    padding-top:20px;
    color:#999;
}

/* RESPONSIVE */

@media(max-width:768px){

    header{
        flex-direction:column;
        gap:15px;
    }

    nav{
        gap:15px;
        flex-wrap:wrap;
        justify-content:center;
    }

    .hero-content h1{
        font-size:42px;
    }

    .banner h2{
        font-size:34px;
    }
}

</style>
</head>
<body>

<header>

<div class="logo">BEATRIX</div>

<nav>
<a href="#">Home</a>
<a href="#">Shoes</a>
<a href="#">Bags</a>
<a href="#">Collection</a>
<a href="#">Contact</a>
</nav>

</header>

<!-- HERO -->

<section class="hero">

<div class="hero-content">
<h1>NEW COLLECTION</h1>
<p>Luxury Fashion Shoes & Bags</p>
<a href="#" class="btn">SHOP NOW</a>
</div>

</section>

<!-- SHOES -->

<section>

<div class="section-title">
<h2>Trending Shoes</h2>
<p>Elegant premium collection</p>
</div>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?q=80&w=1200&auto=format&fit=crop">
<div class="card-content">
<h3>Luxury Sneakers</h3>
<div class="price">Rp 899.000</div>
<button class="buy-btn">Add To Cart</button>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1543163521-1bf539c55dd2?q=80&w=1200&auto=format&fit=crop">
<div class="card-content">
<h3>Elegant Heels</h3>
<div class="price">Rp 1.299.000</div>
<button class="buy-btn">Add To Cart</button>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1600185365483-26d7a4cc7519?q=80&w=1200&auto=format&fit=crop">
<div class="card-content">
<h3>Modern Sneakers</h3>
<div class="price">Rp 799.000</div>
<button class="buy-btn">Add To Cart</button>
</div>
</div>

</div>

</section>

<!-- BAGS -->

<section>

<div class="section-title">
<h2>Luxury Bags</h2>
<p>Modern fashion handbags</p>
</div>

<div class="products">

<div class="card">
<img src="c:\Users\ThinkPad\Downloads\Michael Kors Women’s Shoulder Tote Bag Vanilla.jpg">
<div class="card-content">
<h3>Elegant Handbag</h3>
<div class="price">Rp 5.499.000</div>
<button class="buy-btn">Add To Cart</button>
</div>
</div>

<div class="card">
<img src="c:\Users\ThinkPad\Downloads\Michael Kors Women’s Acorn Signature Pattern Satchel In Dark Brown.jpg">
<div class="card-content">
<h3>Classic Tote Bag</h3>
<div class="price">Rp 5.199.000</div>
<button class="buy-btn">Add To Cart</button>
</div>
</div>

<div class="card">
<img src="c:\Users\ThinkPad\Downloads\Michael Kors Marilyn Women’s Handbag Light in Pink.jpg">
<div class="card-content">
<h3>Shoulder Bag</h3>
<div class="price">Rp 5.899.000</div>
<button class="buy-btn">Add To Cart</button>
</div>
</div>

</div>

</section>

<!-- BANNER -->

<section>

<div class="banner">
<h2>STEP INTO ELEGANCE</h2>
</div>

</section>

<!-- FOOTER -->

<footer>

<div class="footer-grid">

<div>
<h3>BEATRIX</h3>
<p>Luxury fashion store inspired by premium modern fashion brands.</p>
</div>

<div>
<h3>Categories</h3>
<p><a href="#">Sneakers</a></p>
<p><a href="#">Heels</a></p>
<p><a href="#">Handbags</a></p>
<p><a href="#">Accessories</a></p>
</div>

<div>
<h3>Contact</h3>
<p>Instagram: @beatrix.ofc</p>
<p>TikTok: @beatrix.ofc</p>
<p>WhatsApp: +62 812 4703 1733</p>
</div>

</div>

<div class="copy">
© 2026 BEATRIX OFFICIAL
</div>

</footer>

</body>
</html>
