<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Frameology</title>

<style>

body{
margin:0;
font-family:Poppins, sans-serif;
background:#f5f2eb;
color:#111;
}

header{
background:#111;
color:white;
padding:40px;
text-align:center;
letter-spacing:3px;
}

.hero{
height:400px;
display:flex;
align-items:center;
justify-content:center;
flex-direction:column;
background:linear-gradient(to bottom,#111,#333);
color:white;
text-align:center;
}

.hero h1{
font-size:50px;
margin:0;
}

.hero p{
font-size:20px;
opacity:0.8;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
padding:60px;
}

.card{
background:white;
border-radius:12px;
overflow:hidden;
box-shadow:0 10px 25px rgba(0,0,0,0.1);
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
box-shadow:0 15px 35px rgba(0,0,0,0.15);
}

.card img{
width:100%;
height:250px;
object-fit:cover;
}

.card h3{
padding:20px;
margin:0;
text-align:center;
font-weight:500;
}

.special{
background:#111;
color:white;
padding:80px;
text-align:center;
}

footer{
background:#111;
color:white;
text-align:center;
padding:30px;
}

</style>
</head>

<body>

<header>
FRAMEOLOGY
</header>

<section class="hero">
<h1>Turn Memories Into Art</h1>
<p>Premium Instagram Frames & Photo Gifts</p>
</section>

<section class="products">

<div class="card"><img src="https://picsum.photos/400?1"><h3>Instagram Couple Frame</h3></div>
<div class="card"><img src="https://picsum.photos/400?2"><h3>Anniversary Memory Frame</h3></div>
<div class="card"><img src="https://picsum.photos/400?3"><h3>Love Story Timeline Frame</h3></div>
<div class="card"><img src="https://picsum.photos/400?4"><h3>Romantic Photo Collage Frame</h3></div>
<div class="card"><img src="https://picsum.photos/400?5"><h3>Wedding Instagram Frame</h3></div>

<div class="card"><img src="https://picsum.photos/400?6"><h3>Best Friend Frame</h3></div>
<div class="card"><img src="https://picsum.photos/400?7"><h3>Friendship Memory Frame</h3></div>
<div class="card"><img src="https://picsum.photos/400?8"><h3>Squad Photo Frame</h3></div>
<div class="card"><img src="https://picsum.photos/400?9"><h3>College Memories Frame</h3></div>
<div class="card"><img src="https://picsum.photos/400?10"><h3>BFF Instagram Frame</h3></div>

<div class="
