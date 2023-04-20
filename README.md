<!DOCTYPE html>
<html>
<head>
	<title>My Webpage</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<h1>Welcome to My Webpage</h1>
		<nav>
			<ul>
				<li><a href="#about">About</a></li>
				<li><a href="#services">Services</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="about">
			<h2>About Me</h2>
			<p>I am a web developer from [Your City] with experience in HTML, CSS, JavaScript, and other web technologies. </p>
		</section>
		<section id="services">
			<h2>Services</h2>
			<ul>
				<li>Web Development</li>
				<li>Mobile App Development</li>
				<li>Search Engine Optimization</li>
			</ul>
		</section>
		<section id="contact">
			<h2>Contact Me</h2>
			<form>
				<label for="name">Name:</label>
				<input type="text" id="name" name="name" required><br>

				<label for="email">Email:</label>
				<input type="email" id="email" name="email" required><br>

				<label for="message">Message:</label>
				<textarea id="message" name="message" rows="5" cols="30"></textarea><br>

				<input type="submit" value="Submit">
			</form>
		</section>
	</main>
	<footer>
		<p>Copyright © My Webpage</p>
	</footer>
</body>
</html>
