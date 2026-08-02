<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BDGPLAY - Promotional Landing Page</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#0b0b0b;
color:white;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:#111;
border-bottom:1px solid gold;
}

.logo{
font-size:28px;
font-weight:bold;
color:gold;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
}

.hero{
padding:80px 8%;
text-align:center;
}

.hero h1{
font-size:50px;
color:gold;
}

.hero p{
margin-top:20px;
font-size:18px;
color:#ddd;
}

.buttons{
margin-top:35px;
}

.btn{
display:inline-block;
padding:15px 35px;
margin:10px;
border-radius:8px;
text-decoration:none;
font-weight:bold;
}

.gold{
background:gold;
color:black;
}

.dark{
border:2px solid gold;
color:gold;
}

.features{
padding:60px 8%;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
}

.card{
background:#181818;
padding:30px;
border-radius:12px;
border:1px solid #333;
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
border-color:gold;
}

.card h3{
color:gold;
margin-bottom:15px;
}

.download{
text-align:center;
padding:60px;
}

footer{
padding:25px;
text-align:center;
background:#111;
border-top:1px solid gold;
color:#999;
}
</style>

</head>
<body>

<header>

<div class="logo">BDGPLAY</div>

<nav>
<a href="#">Home</a>
<a href="#">Features</a>
<a href="#">FAQ</a>
<a href="#">Contact</a>
</nav>

</header>

<section class="hero">

<h1>Welcome to BDGPLAY</h1>

<p>
Enjoy a modern gaming platform experience with a fast, responsive interface.
</p>

<div class="buttons">

<a href="#" class="btn gold">
Register
</a>

<a href="#" class="btn dark">
Login
</a>

</div>

</section>

<section class="features">

<div class="card">
<h3>Fast Access</h3>
<p>Quick and responsive experience across devices.</p>
</div>

<div class="card">
<h3>Secure Platform</h3>
<p>Designed with user safety and account protection in mind.</p>
</div>

<div class="card">
<h3>24×7 Support</h3>
<p>Support team available whenever assistance is needed.</p>
</div>

<div class="card">
<h3>Mobile Friendly</h3>
<p>Optimized for Android, iPhone and tablets.</p>
</div>

</section>

<section class="download">

<h2 style="color:gold;margin-bottom:20px;">
Download the App
</h2>

<a href="#" class="btn gold">
Download APK
</a>

</section>

<footer>

© 2026 BDGPLAY Promotional Landing Page

</footer>

</body>
</html>