<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Student Applications Portal</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Google Font -->
<link href="https://forms.gle/6Eq4phMZZJDQXpEKA">

<style>

/* =====================
   GLOBAL STYLES
===================== */

*{
box-sizing:border-box;
font-family:Poppins, sans-serif;
}

body{
margin:0;
background:#f4f6f8;
}

/* =====================
   NAVBAR
===================== */

nav{
background:#0b3c5d;
color:white;
padding:15px 25px;
display:flex;
justify-content:space-between;
align-items:center;
}

nav a{
color:white;
text-decoration:none;
margin-left:15px;
cursor:pointer;
}

/* =====================
   SECTIONS
===================== */

section{
display:none;
padding:40px 20px;
}

.active{
display:block;
}

/* =====================
   HERO
===================== */

header{
background:linear-gradient(to right,#0b3c5d,#328cc1);
color:white;
text-align:center;
padding:70px 20px;
}

/* =====================
   GRID
===================== */

.container{
max-width:1100px;
margin:auto;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

/* =====================
   CARD
===================== */

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
text-align:center;
transition:.3s;
}

.card:hover{
transform:translateY(-5px);
}

/* =====================
   BUTTON
===================== */

.btn{
display:inline-block;
background:#328cc1;
color:white;
padding:12px 20px;
border-radius:6px;
text-decoration:none;
margin-top:15px;
border:none;
cursor:pointer;
}

.btn:hover{
background:#1f6fa8;
}

/* =====================
   LOGIN
===================== */

.center{
display:flex;
justify-content:center;
align-items:center;
height:80vh;
}

.login-box{
background:white;
padding:40px;
width:320px;
border-radius:10px;
box-shadow:0 0 15px rgba(0,0,0,.1);
}

.login-box input{
width:100%;
padding:10px;
margin-top:15px;
}

/* =====================
   FOOTER
===================== */

footer{
background:#111;
color:#aaa;
text-align:center;
padding:20px;
margin-top:40px;
}

</style>
</head>

<body>

<!-- NAVBAR -->
<nav>
<div><strong>DEAN OF STUDENT'S PORTAL</strong></div>
<div>
<a onclick="showHome()">Home</a>
<a onclick="showLogin()">Login</a>
<a onclick="logout()">Logout</a>
</div>
</nav>

<!-- HOME -->
<section id="home" class="active">
<header>
<h1>Student Applications Portal</h1>
<p>DEAN OF STUDENT'S OFFICE</p>
</header>

<div class="container">

<div class="card">
<h3>Bursary Application</h3>
<p>Apply for financial assistance.</p>
<a class="btn" href="https://forms.gle/6Eq4phMZZJDQXpEKA" target="_blank">Apply</a>
</div>

<div class="card">
<h3>Work-Study Program</h3>
<p>Apply for part-time campus jobs.</p>
<a class="btn" href="https://forms.gle/6Eq4phMZZJDQXpEKA" target="_blank">Apply</a>
</div>

<div class="card">
<h3>Research Grant</h3>
<p>Apply for research funding.</p>
<a class="btn" href="https://forms.gle/6Eq4phMZZJDQXpEKA" target="_blank">Apply</a>
</div>

<div class="card">
<h3>Other Applications</h3>
<p>Submit other requests.</p>
<a class="btn" href="https://forms.gle/6Eq4phMZZJDQXpEKA" target="_blank">Apply</a>
</div>

</div>
</section>

<!-- LOGIN -->
<section id="login">
<div class="center">
<div class="login-box">
<h2>Student Login</h2>

<input type="text" id="user" placeholder="Student ID">
<input type="password" id="pass" placeholder="Password">

<button class="btn" onclick="login()">Login</button>

<p id="error" style="color:red;"></p>
</div>
</div>
</section>

<!-- DASHBOARD -->
<section id="dashboard">

<header>
<h1>Student Dashboard</h1>
<p>Select an application</p>
</header>

<div class="container">

<div class="card">
<h3>Bursary</h3>
<a class="btn" href="https://forms.gle/6Eq4phMZZJDQXpEKA" target="_blank">Open</a>
</div>

<div class="card">
<h3>Work Study</h3>
<a class="btn" href="https://forms.gle/6Eq4phMZZJDQXpEKA" target="_blank">Open</a>
</div>

<div class="card">
<h3>Research Grant</h3>
<a class="btn" href="https://forms.gle/YOURFORM" target="_blank">Open</a>
</div>

<div class="card">
<h3>EXAM CARD</h3>
<a class="btn" href="https://forms.gle/YOURFORM" target="_blank">Open</a>
</div>

<div class="card">
<h3>OTHERS</h3>
<a class="btn" href="https://forms.gle/YOURFORM" target="_blank">Open</a>
</div>

</div>
</section>

<!-- FOOTER -->
<footer>
© 2026 UNIVERSITY OF ELDORET| Dean of Students’ Office
</footer>

<script>

/* =====================
   PAGE CONTROL
===================== */

function hideAll(){
document.getElementById("home").classList.remove("active");
document.getElementById("login").classList.remove("active");
document.getElementById("dashboard").classList.remove("active");
}

function showHome(){
hideAll();
document.getElementById("home").classList.add("active");
}

function showLogin(){
hideAll();
document.getElementById("login").classList.add("active");
}

function showDashboard(){
hideAll();
document.getElementById("dashboard").classList.add("active");
}

/* =====================
   LOGIN SYSTEM
===================== */

function login(){
let u=document.getElementById("user").value;
let p=document.getElementById("pass").value;

if(u==="student" && p==="1234"){
showDashboard();
document.getElementById("error").innerHTML="";
}
else{
document.getElementById("error").innerHTML="Invalid Login";
}
}

function logout(){
showHome();
}

</script>

</body>
</html>
