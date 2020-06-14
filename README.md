
<html>
<head>
	<title>Responsive website</title>
	<link rel="stylesheet" type="text/css" href="styles.css">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link href="https://fonts.googleapis.com/css2?family=Catamaran:wght@300&display=swap" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond&display=swap" rel="stylesheet">
	
<style>
* {
	text-decoration: none;
}

header{
	background-color: #fff;
	width: 100%;
	height: 100px;
}

header .header-brand{
	font-family: 'Catamaran', sans-serif;
	font-size: 14px;
	font-weight: 900;
	color: #111;
	text-transform: uppercase;
	display: block;
	margin: 0 auto;
	text-align: center;
	padding: 20px 0;
}


header nav ul{
	display: block;
	margin: 0 auto;
	width:fit-content;
}

header nav ul li {
	display: inline-block;
	float: left;
	list-style: none;
	padding: 0 16px;
}
	


header nav ul li a {
	font-family: 'Catamaran', sans-serif;
	font-size: 16px;
	color: #111;
	text-transform: uppercase;
	line-height: 60px;
}


header .header-cases{
	display: none;
}

@media only screen and (min-width: 1000px) {
	header .header-brand{
	margin: 31px 0;
	text-align: left;
	line-height: 38px;
	padding: 0 20px 0 40px;
	border-right: 3px solid #111;
	float: left;
  }

  header nav ul {
	margin: 20px 0 0 20px;
	float: left;
}


header nav ul li a {
	line-height: 60px;

	}

header .header-cases {
	display: block;
	font-family: 'Catamaran', sans-serif;
	font-size: 16px;
	color: #111;
	text-transform: uppercase;
	line-height: 38px;
	border: 1px solid #111;
	float: right;
	margin-right: 40px;
	margin-top: 30px;
	padding: 0 20px;
	
	}
}

/*INDEX PAGE*/

.index-banner{
	width: 100%;
	height: calc(100vh- 100px);
	background-image: url("webpic2.jpg"); 
	background-repeat: no-repeat;
	background-position: center;
	background-size: cover;
	display: table;

}

.vertical-center{
	display: table-cell;
	vertical-align: middle;

}

.index-banner h2{
	font-family: 'Catamaran', sans-serif;
	font-size: 60px;
	font-weight: 900;
	line-height: 70px;
	color: #fff;
	text-align: center;
	text-shadow: 2px 2px #111;
}

.index-banner h1{
	font-family:'Cormorant Garamond', serif;
	font-size: 28px;
	font-style: italic;
	font-weight: 100;
	line-height: 34px;
	color: #fff;
	text-align: center;
	text-shadow: 2px 2px #111;

}

.index-links div {
	margin: 16px 16px 0;
	width: calc(100% - 32px);
	height: 100px;
	background-color: #f2f2f2;
}

.index-links div h3 {
	font-family:'Catamaran', sans-serif;
	font-size: 28px;
	font-weight: 600;
	line-height: 100px;
	color: #111;
	text-align: center;
	text-transform: uppercase;
}

@media only screen and (min-width: 1000px) {
	.wrapper {
		width: 1000px;
		margin: 0 auto;
	}

	.index-banner {
		height: 450px;
	}

	.index-banner h1 {
		display: block;
		width: 560px;
		margin: 0 auto;
}

	.index-links {
		overflow: hidden;
	}

	.index-links div {
		margin: 20px 10px 0;
		height: 230px;
		background-color: #f2f2f2;
		float: left;
}
	.index-boxlink-square {
		width: calc(25% - 20px) !important;
	}
	.index-boxlink-rectangle {
		width: calc(50% - 20px) !important;
	}

	.index-links div h3 {
		line-height: 170px;
}

}

/*FOOTER*/

footer {
	widows: calc(100% - 80px);
	padding: 40px 40px;
	margin: 20px;
	background-color: #111;
	overflow: hidden;
}

footer ul {
	width: fit-content;
	float: left;
	padding-left: 20px;
}

footer ul li {
	display: block;
	list-style: none;
}

footer ul li a {
	font-family: 'Catamaran', sans-serif;
	font-size: 24px;
	color: #fff;
	line-height: 30px;
}

.footer-links-cases {
	display: none;
}

.footer-sm {
	width: 50px;
	float: right;
}

.footer-sm img {
	width: 100%;
	margin-bottom: 10px;

}


@media only screen and (min-width: 1000px) {
	.footer-links-cases {
	display: block;
}

footer ul {

	padding-right: 30px;
}


footer ul li p {
	font-family: 'Catamaran';
	font-size: 24px;
	color: #fff;
	line-height: 40px;
	text-transform: uppercase;

}

</style>
<body>
	<header>
		<a href="responsive.html" class="header-brand">PRE</a>
		<nav>
			<ul>
				<li><a href="portfolio.html">Portfolio</a></li>
				<li><a href="about.html">About Me</a></li>
				<li><a href="contact.html">Contact</a></li>
			</ul>
			<a href="cases.html" class="header-cases">Cases</a>
		</nav>
	</header>
	<main>
		<section class="index-banner">
			<div class="vertical-center">
				<h2>I AM A FREELANCE WEB<br>DEVELOPER</h2>
				<h1>With specialty in front-end development, functionality, ux design, back-end, search engine optimization, and scalability</h1>


		
		<div class="wrapper">
		<section class="index-links">
			<a href="#">
				<div class="index-boxlink-square">
					<h3>Cases</h3>
				</div>	
			</a>
				<div class="index-boxlink-rectangle">
					<h3>Portfolio</h3>
				</div>	
			<a href="#">
				<div class="index-boxlink-square">
					<h3>PRE</h3>
				</div>
			</a>
			<a href="#">
				<div class="index-boxlink-rectangle">
					<h3>YouTube Channel</h3>
				</div>	
			</a>
			<a href="#">
				<div class="index-boxlink-square">
					<h3>About</h3>
				</div>	
			</a>
			<a href="#">
				<div class="index-boxlink-square">
					<h3>Contact</h3>
				</div>	
			</a>
		
	</div>
	
	<div class="wrapper">
	<footer>
		<ul class="footer-links-main">
			<li><a href="#">Home</a></li>
			<li><a href="#">Cases</a></li>
			<li><a href="#">Portforlio</a></li>
			<li><a href="#">About Me</a></li>
			<li><a href="#">Contact</a></li>
		</ul>
		<ul class="footer-links-cases">
			<li><p>Lastest Cases</p></li>
			<li><a href="#">MAILING PATTI - WEB DEVELOPMENT</a></li>
			<li><a href="#">EXCELLENTO - WEB DEVELOPMENT, SEO</a></li>
			<li><a href="#">PRE - YOUTUBE CHANNEL</a></li>
			<li><a href="#">WELTEC - VIDEO PRODUCTION</a></li>
		</ul>
		<div class="footer-sm">
			<a href="#">
				<img src="youtube.png" alt="youtube icon">
			</a>
			<a href="#">
				<img src="twitter.png" alt="twitter icon">
			</a>
			<a href="#">
				<img src="facebook.png" alt="facebook icon">
			</a>
		</div>

	</footer>
</div>
</body>
</html>
