# BDGPLAY
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Website</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f4f4f4;
color:#333;
}

header{
background:#0f172a;
color:white;
padding:20px;
text-align:center;
}

nav{
background:#1e293b;
padding:10px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:15px;
font-weight:bold;
}

.hero{
padding:80px 20px;
text-align:center;
background:linear-gradient(135deg,#2563eb,#06b6d4);
color:white;
}

.hero h1{
font-size:48px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
margin-bottom:30px;
}

.btn{
display:inline-block;
padding:15px 30px;
background:white;
color:#2563eb;
text-decoration:none;
border-radius:8px;
font-weight:bold;
}

.services{
padding:60px 20px;
text-align:center;
}

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
}

.card{
background:white;
padding:20px;
width:300px;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
}

footer{
background:#0f172a;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}
</style>

</head>

<body>

<header>
<h2>My Business Website</h2>
</header>

<nav>
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Services</a>
<a href="#">Contact</a>
</nav>

<section class="hero">
<h1>Welcome to My Website</h1>
<p>Professional Website for Business & SEO</p>
<a href="#" class="btn">Get Started</a>
</section>

<section class="services">
<h2>Our Services</h2>
<br>

<div class="cards">

<div class="card">
<h3>Website Design</h3>
<p>Modern responsive websites for your business.</p>
</div>

<div class="card">
<h3>SEO</h3>
<p>Rank your website higher on Google Search.</p>
</div>

<div class="card">
<h3>Digital Marketing</h3>
<p>Grow your business with online marketing.</p>
</div>

</div>

</section>

<footer>
<p>© 2026 My Website. All Rights Reserved.</p>
</footer>

</body>
</html>