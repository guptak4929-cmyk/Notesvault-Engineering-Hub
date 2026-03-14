<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>CodewithADSC</title>

<style>

body{
margin:0;
font-family: 'Segoe UI', sans-serif;
background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
color:white;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:rgba(0,0,0,0.5);
}

.logo{
font-size:24px;
font-weight:bold;
color:#00d9ff;
}

nav a{
margin:0 15px;
text-decoration:none;
color:white;
font-size:16px;
transition:0.3s;
}

nav a:hover{
color:#00d9ff;
}

.hero{
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
height:80vh;
padding:20px;
}

.hero h1{
font-size:50px;
margin-bottom:20px;
}

.hero p{
max-width:600px;
font-size:18px;
opacity:0.9;
}

.btn{
margin-top:25px;
padding:15px 30px;
background:#00d9ff;
color:black;
font-weight:bold;
border:none;
border-radius:30px;
cursor:pointer;
transition:0.3s;
}

.btn:hover{
background:white;
transform:scale(1.05);
}

.section{
padding:60px 10%;
text-align:center;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
margin-top:30px;
}

.card{
background:rgba(255,255,255,0.05);
padding:25px;
border-radius:10px;
transition:0.3s;
}

.card:hover{
transform:translateY(-10px);
background:rgba(255,255,255,0.1);
}

footer{
text-align:center;
padding:20px;
background:black;
margin-top:40px;
}

</style>
</head>

<body>

<header>
<div class="logo">CodewithADSC</div>

<nav>
<a href="#">Home</a>
<a href="#">Python</a>
<a href="#">Practice</a>
<a href="#">Resources</a>
<a href="#">Contact</a>
</nav>
</header>

<section class="hero">

<h1>UNLOCK YOUR CODING POTENTIAL</h1>

<p>
Learn Python programming, improve coding skills, and build amazing projects.
Join our coding community and start your journey as a developer.
</p>

<button class="btn">Start Learning Python</button>

</section>

<section
