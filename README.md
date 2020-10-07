# Business-website


# index.html

<!DOCTYPE html>
<html>
<head>
	<title>Business Website</title>
	<link href="style.css" rel="stylesheet" type="text/css">
</head>
<body>
	<header>
		<div class="row">
			<div class="logo">
			<img src="logo1.jpg">	
			</div>
			<ul class="main-nav">
				<li class="active"> <a href="">HOME</a></li>
				<li> <a href="">SERVICES</a></li>
				<li> <a href="">ABOUT</a></li>
				<li> <a href="">CONTACT</a></li>
				<li> <a href="">NEWS</a></li>
				<li> <a href="">FAQ</a></li>
				

			</ul>
			
		</div>
		<div class="Hero">
			<h1>Are You Ready</h1>

			<div class="button">
				<a href="" class="btn btn-one">Watch Video</a>
				<a href="" class="btn btn-two">Watch Video</a>
			</div>
			
		</div>
		

	</header>



</body>
</html>

# style.css

*
{
	margin: 0;
	padding: 0;
}

header 
{
	background-image: linear-gradient(rgba(0,0,0,0.5)),url(pics1.jpg);
	height: 100vh;
	background-size: cover;
	background-position: center;
}

.main-nav 
{
	float:right;
	list-style: none;
	margin-top: 30px;
}

.maim-nav li
{
	display: inline-block;
}


.main-nav li a 
{
	color: white;
	text-decoration: none;
	padding: 5px 20px;
	font-family: "Roboto", sans-serif;
	font-size: 15px;
}

.main-nav li.active a
{
	border: 1px solid white;
}

.main-nav li a:hover
{
	border: 1px solid white;
}

.logo img
{
	width: 150px;
	height: auto;
	floart: left;
}

body
{
	font-family: monospace;
}

.row
{
	max-width: 120px;
	margin:auto;
}

.Hero
{
	position: absolute;
	width: 1200px;
	margin-left: 0px;
	margin-top: 0px;
}

h1
{
	color:white;
	text-transform: uppercase;
	font-size: 70px;
	text-align: center;
	margin-top: 275px;

}

.button
{
	margin-top: 30px;
	margin-left: 440px;
}

.btn
{
	border: 1px solid white;
	padding: 10px 30px;
	color: white;
	
}



