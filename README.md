<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">

<title>MotorScore - America's Smartest Car Marketplace</title>

<meta name="viewport" content="width=device-width, initial-scale=1">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
}

body{
background:#f5f5f5;
}

header{

background:#111;
color:white;
padding:20px;
display:flex;
justify-content:space-between;
align-items:center;

}

.logo{

font-size:34px;
font-weight:bold;
color:#e11d2f;

}

nav a{

color:white;
margin-left:25px;
text-decoration:none;

}

.hero{

background:url("https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1800&q=80");
background-size:cover;
background-position:center;
height:550px;

display:flex;
justify-content:center;
align-items:center;

}

.search-box{

background:white;
padding:40px;
border-radius:10px;
width:900px;
text-align:center;

}

.search-box h1{

margin-bottom:25px;
font-size:40px;

}

input,select{

padding:15px;
margin:10px;
width:220px;

}

button{

padding:16px 30px;
background:#d5001c;
color:white;
border:none;
cursor:pointer;
font-size:18px;

}

.section{

padding:60px;

}

.cards{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;

}

.card{

background:white;
padding:25px;
border-radius:10px;
box-shadow:0 0 15px rgba(0,0,0,.12);

}

.card h2{

margin-bottom:10px;

}

.score{

font-size:42px;
color:#d5001c;
font-weight:bold;

}

footer{

background:#111;
color:white;
padding:30px;
text-align:center;

}

</style>

</head>

<body>

<header>

<div class="logo">

MotorScore

</div>

<nav>

<a href="#">Search</a>

<a href="#">Reviews</a>

<a href="#">Compare</a>

<a href="#">Market Value</a>

<a href="#">Investment</a>

<a href="#">Garage</a>

<a href="#">Login</a>

</nav>

</header>

<section class="hero">

<div class="search-box">

<h1>Find Your Perfect Car</h1>

<select>

<option>Make</option>
<option>Porsche</option>
<option>Ferrari</option>
<option>Lamborghini</option>
<option>McLaren</option>
<option>BMW</option>
<option>Mercedes</option>

</select>

<select>

<option>Model</option>

</select>

<select>

<option>Year</option>

</select>

<input type="text" placeholder="ZIP Code">

<br><br>

<button>Search Inventory</button>

</div>

</section>

<section class="section">

<h1>MotorScore AI Rankings</h1>

<br>

<div class="cards">

<div class="card">

<h2>2021 Porsche 911 Turbo S</h2>

<div class="score">98</div>

<p>Overall MotorScore</p>

</div>

<div class="card">

<h2>Ferrari F8 Spider</h2>

<div class="score">97</div>

<p>Performance Score</p>

</div>

<div class="card">

<h2>Lamborghini STO</h2>

<div class="score">96</div>

<p>Track Score</p>

</div>

<div class="card">

<h2>GT3 RS</h2>

<div class="score">99</div>

<p>Driver Score</p>

</div>

</div>

</section>

<section class="section">

<h1>Featured Tools</h1>

<br>

<div class="cards">

<div class="card">

<h2>AI Car Finder</h2>

<p>Describe what you want and AI recommends vehicles.</p>

</div>

<div class="card">

<h2>Market Value</h2>

<p>See today's estimated market value.</p>

</div>

<div class="card">

<h2>Investment Rating</h2>

<p>Predict appreciation over 10 years.</p>

</div>

<div class="card">

<h2>Reliability Score</h2>

<p>Historical reliability from thousands of owners.</p>

</div>

<div class="card">

<h2>Ownership Cost</h2>

<p>Insurance, maintenance, depreciation.</p>

</div>

<div class="card">

<h2>Horsepower Rankings</h2>

<p>Every production vehicle ranked.</p>

</div>

<div class="card">

<h2>0-60 Rankings</h2>

<p>Fastest production cars.</p>

</div>

<div class="card">

<h2>Quarter Mile Rankings</h2>

<p>Verified drag strip results.</p>

</div>

</div>

</section>

<section class="section">

<h1>Featured Vehicles</h1>

<br>

<div class="cards">

<div class="card">

<h2>Ferrari SF90 Spider</h2>

<p>$575,000</p>

<p>MotorScore 99</p>

</div>

<div class="card">

<h2>Porsche GT2 RS</h2>

<p>$729,000</p>

<p>Collector Grade A+</p>

</div>

<div class="card">

<h2>McLaren 765LT Spider</h2>

<p>$499,000</p>

<p>Investment Score 95</p>

</div>

<div class="card">

<h2>Lamborghini Revuelto</h2>

<p>$700,000</p>

<p>Future Value ★★★★★</p>

</div>

</div>

</section>

<section class="section">

<h1>Compare Cars</h1>

<br>

<div class="cards">

<div class="card">

<h2>Performance</h2>

<p>Horsepower</p>
<p>Torque</p>
<p>Top Speed</p>
<p>0-60</p>
<p>Quarter Mile</p>

</div>

<div class="card">

<h2>Ownership</h2>

<p>Insurance</p>
<p>Maintenance</p>
<p>Fuel</p>
<p>Depreciation</p>

</div>

<div class="card">

<h2>Ratings</h2>

<p>MotorScore</p>
<p>Reliability</p>
<p>Luxury</p>
<p>Comfort</p>

</div>

<div class="card">

<h2>Investment</h2>

<p>5 Year Prediction</p>
<p>10 Year Prediction</p>
<p>Collector Index</p>

</div>

</div>

</section>

<footer>

<h2>MotorScore</h2>

<p>

America's Smartest Car Marketplace

</p>

<p>

© 2026 MotorScore

</p>

</footer>

</body>

</html>
