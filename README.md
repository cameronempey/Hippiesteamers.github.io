<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <a href="/">Home</a>
      <a href="/services">Services</a>
      <a href="/about">About Us</a>
      <a href="/contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to Your Website</h1>
    <p>We provide top-notch cleaning services.</p>
    <a href="/book" class="cta-button">Book Now</a>
  </section>

  <footer>
    <p>&copy; 2023 Your Company. All rights reserved.</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: white;
  padding: 1rem;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 1rem;
  text-decoration: none;
}

.hero {
  background-image: url('hero-image.jpg');
  background-size: cover;
  color: white;
  text-align: center;
  padding: 5rem 1rem;
}

.cta-button {
  background-color: #ff6600;
  color: white;
  padding: 0.5rem 1rem;
  text-decoration: none;
  border-radius: 5px;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1rem;
  position: fixed;
  bottom: 0;
  width: 100%;
}
