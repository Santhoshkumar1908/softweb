# Ex.06 Restuarant Website
## Date:24-05-2026

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
home.html:
~~~
<!DOCTYPE html>
<html>
<head>
<title>Home</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f2f2f2;
}

header{
background:darkred;
color:white;
padding:20px;
text-align:center;
}

nav{
background:black;
padding:15px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:20px;
}

section{
padding:40px;
text-align:center;
}

footer{
background:black;
color:white;
padding:15px;
text-align:center;
margin-top:30px;
}

</style>

</head>

<body>

<header>
<h1>Spice Heaven Restaurant</h1>
</header>

<nav>
<a href="home.html">Home</a>
<a href="menu.html">Menu</a>
<a href="team.html">Team</a>
<a href="contact.html">Contact</a>
</nav>

<section>

<h2>Welcome</h2>

<p>
Enjoy delicious food and quality service at Spice Heaven Restaurant.
Fresh ingredients and tasty dishes every day.
</p>

<img src="WhatsApp Image 2026-05-24 at 10.52.28 PM.jpeg" width="500">

</section>

<footer>
Developed by Santhoshkumar J.
</footer>

</body>
</html>
~~~
menu.html:
~~~
<!DOCTYPE html>
<html>
<head>
<title>Menu</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f2f2f2;
}

h1{
background:orange;
color:white;
padding:20px;
text-align:center;
}

nav{
background:black;
padding:15px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:20px;
}

.container{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
padding:20px;
}

.card{
background:white;
width:220px;
padding:15px;
text-align:center;
border-radius:10px;
box-shadow:0 0 8px gray;
}

img{
width:180px;
height:120px;
border-radius:10px;
}

footer{
background:black;
color:white;
padding:15px;
text-align:center;
}

</style>

</head>

<body>

<h1>Our Menu</h1>

<nav>
<a href="home.html">Home</a>
<a href="menu.html">Menu</a>
<a href="team.html">Team</a>
<a href="contact.html">Contact</a>
</nav>

<div class="container">

<div class="card">
<img src="briyani.jpeg">
<h3>Chicken Biryani</h3>
<p>₹270</p>
</div>

<div class="card">
<img src="fried rice.jpeg">
<h3>Fried Rice</h3>
<p>₹150</p>
</div>

<div class="card">
<img src="pizza.jpeg">
<h3>Pizza</h3>
<p>₹170</p>
</div>

<div class="card">
<img src="burger.jpeg">
<h3>Burger</h3>
<p>₹120</p>
</div>

<div class="card">
<img src="paneer BBQ.jpeg">
<h3>Paneer Tikka</h3>
<p>₹170</p>
</div>

<div class="card">
<img src="special Thai Noodles.jpeg">
<h3>Noodles</h3>
<p>₹150</p>
</div>

<div class="card">
<img src="Classical Mix.jpeg">
<h3>Ice Cream</h3>
<p>₹90</p>
</div>

</div>

<footer>
Developed by Santhoshkumar J.
</footer>

</body>
</html>
~~~
team.html:
~~~
<!DOCTYPE html>
<html>
<head>
<title>Team</title>

<style>

body{
margin:0;
font-family:Arial;
background:#eeeeee;
}

h1{
background:green;
color:white;
padding:20px;
text-align:center;
}

nav{
background:black;
padding:15px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:20px;
}

.container{
display:grid;
grid-template-columns:auto auto auto;
gap:20px;
padding:30px;
}

.card{
background:white;
padding:20px;
text-align:center;
border-radius:10px;
}

footer{
background:black;
color:white;
padding:15px;
text-align:center;
}

</style>

</head>

<body>

<h1>Our Team</h1>

<nav>
<a href="home.html">Home</a>
<a href="menu.html">Menu</a>
<a href="team.html">Team</a>
<a href="contact.html">Contact</a>
</nav>

<div class="container">

<div class="card">Chef Arun</div>

<div class="card">Chef Priya</div>

<div class="card">Chef Meena</div>

<div class="card">Manager Rahul</div>

<div class="card">Server Ajay</div>

<div class="card">Server Kavya</div>

<div class="card">Cashier Deepak</div>

</div>

<footer>
Developed by Santhoshkumar J.
</footer>

</body>
</html>
~~~
contact.html:
~~~
<!DOCTYPE html>
<html>
<head>
<title>Contact</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f2f2f2;
}

h1{
background:blue;
color:white;
padding:20px;
text-align:center;
}

nav{
background:black;
padding:15px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:20px;
}

section{
padding:40px;
text-align:center;
}

footer{
background:black;
color:white;
padding:15px;
text-align:center;
margin-top:30px;
}

</style>

</head>

<body>

<h1>Contact Us</h1>

<nav>
<a href="home.html">Home</a>
<a href="menu.html">Menu</a>
<a href="team.html">Team</a>
<a href="contact.html">Contact</a>
</nav>

<section>

<h2>Restaurant Details</h2>

<p>Address : Chennai, Tamil Nadu</p>

<p>Phone : 9876543210</p>

<p>Email : spiceheaven@gmail.com</p>

</section>

<footer>
Developed by Santhoshkumar J.
</footer>

</body>
</html>
~~~

## OUTPUT:
![alt text](<web/softapp/static/Screenshot 2026-05-24 232940.png>)
![alt text](<web/softapp/static/Screenshot 2026-05-24 233006.png>)
![alt text](<web/softapp/static/Screenshot 2026-05-24 233028.png>)
![alt text](<web/softapp/static/Screenshot 2026-05-24 233051.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
