
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>CSS NWEOL BATCH 2013</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Segoe UI,sans-serif;
}

body{
background:#f5f7fa;
}

/* HERO SECTION */

.hero{
height:100vh;
background:
linear-gradient(rgba(0,0,50,0.7),
rgba(0,0,50,0.7)),
url("background.jpg");

background-size:cover;
background-position:center;
color:white;
}

/* NAVIGATION */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 60px;
}

.logo{
display:flex;
align-items:center;
gap:15px;
}

.logo img{
width:70px;
height:70px;
border-radius:50%;
background:white;
}

.logo h2{
font-size:24px;
}

.menu a{
color:white;
text-decoration:none;
margin-left:25px;
font-weight:bold;
transition:0.3s;
}

.menu a:hover{
color:gold;
}

/* WELCOME TEXT */

.hero-content{
height:80%;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.hero-content h1{
font-size:60px;
margin-bottom:15px;
}

.hero-content p{
font-size:22px;
max-width:800px;
line-height:1.7;
}

.btn{
display:inline-block;
margin-top:30px;
padding:15px 35px;
background:gold;
color:black;
text-decoration:none;
font-weight:bold;
border-radius:30px;
}

/* MOTTO */

.motto{
background:white;
padding:50px;
text-align:center;
}

.motto h2{
color:#0b1f4d;
margin-bottom:15px;
}

/* EXECUTIVES */

.executives{
padding:70px 10%;
}

.executives h2{
text-align:center;
font-size:40px;
color:#0b1f4d;
margin-bottom:40px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:30px;
}

.card{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 5px 20px rgba(0,0,0,0.15);
transition:0.4s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
height:250px;
object-fit:cover;
}

.card h3{
padding:15px;
text-align:center;
color:#0b1f4d;
}

/* OBJECTIVES */

.objectives{
padding:70px 10%;
background:#eef2f8;
}

.objectives h2{
text-align:center;
color:#0b1f4d;
margin-bottom:30px;
}

.objective-box{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.objective-box li{
margin:15px;
font-size:18px;
}

/* FOOTER */

footer{
background:#061433;
color:white;
text-align:center;
padding:25px;
}

</style>
</head>

<body>

<div class="hero">

<nav>

<div class="logo">
<img src="img_1950.jpg">
<h2>CSS NWEOL BATCH 2013</h2>
</div>

<div class="menu">
<a href="monthly-dues.html">Monthly Dues</a>
<a href="financial-report.html">Financial Report</a>
<a href="gallery.html">Gallery</a>
<a href="achievements.html">Achievements</a>
<a href="contact.html">Contact Us</a>
</div>

</nav>

<div class="hero-content">

<h1>Welcome Home Alumni</h1>

<p>
A community built on friendship, unity, support and service.
Together we celebrate success, support one another and contribute
to the growth of our members and society.
</p>

<a href="gallery.html" class="btn">Explore Our Activities</a>

</div>

</div>

<section class="motto">

<h2>OUR MOTTO</h2>

<p><strong>Unity • Progress • Service</strong></p>

</section>

<section class="executives">

<h2>Executive Council</h2>

<div class="cards">

<div class="card">
<img src="president.jpg">
<h3>President</h3>
</div>

<div class="card">
<img src="vice-president.jpg">
<h3>Vice President</h3>
</div>

<div class="card">
<img src="secretary.jpg">
<h3>Secretary</h3>
</div>

<div class="card">
<img src="treasurer.jpg">
<h3>Treasurer</h3>
</div>

<div class="card">
<img src="provost.jpg">
<h3>Provost</h3>
</div>

</div>

</section>

<section class="objectives">

<h2>Aims & Objectives</h2>

<div class="objective-box">

<ul>
<li>Promote unity among members.</li>
<li>Provide welfare support to members.</li>
<li>Strengthen friendship and networking.</li>
<li>Support community development projects.</li>
<li>Celebrate and assist members during important life events.</li>
</ul>

</div>

</section>

<footer>

CSS NWEOL BATCH 2013 Alumni Association © 2026

</footer>

</body>
</html>
