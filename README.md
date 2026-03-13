<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Galaxy Bistro</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css"/>
<style>
body{margin:0;font-family:'Poppins',sans-serif;background:#0f1117;color:white;}
header{text-align:center;padding:140px;background:linear-gradient(180deg,#0f1117,#1b1e2b);}
header h1{font-size:48px;margin-bottom:15px;}
header p{font-size:18px;color:#b9b9b9;margin-bottom:30px;}
.btn{display:inline-block;margin:10px;padding:12px 26px;background:#4f7cff;border-radius:8px;color:white;text-decoration:none;transition:0.3s;}
.btn:hover{background:#3556d8;transform:translateY(-3px);}
section{padding:80px 20px;}
.container{width:90%;max-width:1100px;margin:auto;}
.menu-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:25px;margin-top:40px;}
.menu-item{background:#171b2a;padding:25px;border-radius:12px;transition:0.3s;}
.menu-item:hover{transform:translateY(-8px);background:#1e2340;}
footer{text-align:center;padding:30px;background:#0b0d13;color:#777;}
</style>
</head>
<body>

<header data-aos="fade-up">
<h1>Galaxy Bistro</h1>
<p>Modern urban cuisine restaurant</p>
<a class="btn" href="#menu">View Menu</a>
</header>

<section class="container" id="menu" data-aos="fade-up">
<h2>Our Menu</h2>
<div class="menu-grid">
<div class="menu-item" data-aos="zoom-in">Carbonara Pasta</div>
<div class="menu-item" data-aos="zoom-in">Galaxy Burger</div>
<div class="menu-item" data-aos="zoom-in">Caesar Salad</div>
<div class="menu-item" data-aos="zoom-in">Tom Yum Soup</div>
<div class="menu-item" data-aos="zoom-in">Margherita Pizza</div>
<div class="menu-item" data-aos="zoom-in">Tiramisu Dessert</div>
</div>
</section>

<footer>
© 2026 Galaxy Bistro
</footer>

<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
AOS.init({duration:1000,once:true});
</script>
</body>
</html>
