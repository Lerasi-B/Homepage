
<html>
<head>
    <title>CSS NWEOL BATCH 2013</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
        }

        body{
            font-family: Arial, sans-serif;
            background:#f4f6f9;
            color:#333;
        }

        header{
            background:#0b1f4d;
            color:white;
            text-align:center;
            padding:20px;
        }

        .logo{
            width:120px;
            height:120px;
            border-radius:50%;
        }

        nav{
            background:#061433;
            text-align:center;
            padding:15px;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:15px;
            font-weight:bold;
            padding:10px 15px;
        }

        nav a:hover{
            background:gold;
            color:black;
            border-radius:5px;
        }

        .hero{
            background:url("background.jpg");
            background-size:cover;
            background-position:center;
            color:white;
            text-align:center;
            padding:80px 20px;
        }

        .hero h1{
            font-size:40px;
        }

        .section{
            width:90%;
            margin:auto;
            padding:40px 0;
        }

        .section h2{
            text-align:center;
            color:#0b1f4d;
            margin-bottom:20px;
        }

        .objectives{
            background:white;
            padding:25px;
            border-radius:10px;
            box-shadow:0 0 10px rgba(0,0,0,0.1);
        }

        .executives{
            display:flex;
            flex-wrap:wrap;
            justify-content:center;
            gap:20px;
        }

        .card{
            background:white;
            width:200px;
            border-radius:10px;
            overflow:hidden;
            box-shadow:0 0 10px rgba(0,0,0,0.2);
            text-align:center;
        }

        .card img{
            width:100%;
            height:220px;
            object-fit:cover;
        }

        .card h3{
            padding:10px;
            color:#0b1f4d;
        }

        footer{
            background:#061433;
            color:white;
            text-align:center;
            padding:20px;
            margin-top:30px;
        }
    </style>
</head>

<body>

<header>

    <img src="logo.png" class="logo">

    <h1>CSS NWEOL BATCH 2013</h1>

    <h3>Motto: Unity, Progress and Service</h3>

</header>

<nav>
    <a href="monthly-dues.html">Monthly Dues</a>
    <a href="financial-report.html">Financial Report</a>
    <a href="contact.html">Contact Us</a>
    <a href="gallery.html">Gallery</a>
    <a href="achievements.html">Past Achievements</a>
</nav>

<div class="hero">
    <h1>Welcome to CSS NWEOL BATCH 2013</h1>
    <p>Together we build friendship, unity and support one another.</p>
</div>

<div class="section">

    <h2>Our Aim & Objectives</h2>

    <div class="objectives">

        <ul>
            <li>Promote unity among members.</li>
            <li>Support members during celebrations and challenges.</li>
            <li>Encourage networking and friendship.</li>
            <li>Carry out community development projects.</li>
            <li>Provide welfare assistance to members.</li>
        </ul>

    </div>

</div>

<div class="section">

    <h2>Executive Members</h2>

    <div class="executives">

        <div class="card">
            <img src="president.jpg">
            <h3>John Doe<br>President</h3>
        </div>

        <div class="card">
            <img src="vice-president.jpg">
            <h3>Jane Doe<br>Vice President</h3>
        </div>

        <div class="card">
            <img src="secretary.jpg">
            <h3>Michael Smith<br>Secretary</h3>
        </div>

        <div class="card">
            <img src="treasurer.jpg">
            <h3>Mary Johnson<br>Treasurer</h3>
        </div>

        <div class="card">
            <img src="provost.jpg">
            <h3>David Brown<br>Provost</h3>
        </div>

    </div>

</div>

<footer>
    © 2026 CSS NWEOL BATCH 2013 Alumni Association
</footer>

</body>
</html>
