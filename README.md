<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Simba Print - Vintage Graphic Design</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display&family=Roboto&display=swap');
  :root {
    --gold: #d4af37;
    --white: #fff;
    --luminous-green: #39ff14;
    --luminous-red: #ff073a;
    --dark-charcoal: #2b2b2b;
    --dark-brown: #4b2e05;
  }
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0; 
    font-family: 'Roboto', sans-serif;
    background-color: var(--white);
    color: var(--dark-charcoal);
  }
  header {
    background-color: var(--gold);
    padding: 1rem 2rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  header .logo {
    font-family: 'Playfair Display', serif;
    font-size: 1.8rem;
    font-weight: bold;
    color: var(--dark-brown);
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }
  header .logo img {
    height: 40px;
    width: 40px;
  }
  nav a {
    color: var(--dark-brown);
    text-decoration: none;
    margin-left: 1.5rem;
    font-weight: 600;
    font-size: 1rem;
  }
  nav a:hover {
    color: var(--luminous-green);
  }
  main {
    padding: 2rem;
    max-width: 900px;
    margin: 0 auto;
  }
  .hero {
    text-align: center;
    padding: 3rem 1rem;
  }
  .hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: 3rem;
    color: var(--gold);
    margin-bottom: 1rem;
  }
  .hero p {
    font-size: 1.2rem;
    color: var(--dark-brown);
    max-width: 600px;
    margin: 0 auto;
  }
  footer {
    background-color: var(--dark-brown);
    color: var(--white);
    text-align: center;
    padding: 1rem;
    margin-top: 3rem;
  }
  /* Responsive */
  @media (max-width: 600px) {
    header {
      flex-direction: column;
      gap: 1rem;
    }
    nav a {
      margin-left: 0;
      margin-right: 1rem;
    }
  }
</style>
</head>
<body>
<header>
  <div class="logo">
    <img src="https://cdn-icons-png.flaticon.com/512/616/616408.png" alt="Simba Print Lion Logo" />
    Simba Print
  </div>
  <nav>
    <a href="#home">Home</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <section class="hero" id="home">
    <h1>Welcome to Simba Print</h1>
    <p>Bringing vintage charm and timeless style to your brand with expertly crafted logos, flyers, and brand identity designs.</p>
  </section>
</main>

<footer>
  &copy; 2025 Simba Print. All rights reserved.
</footer>
</body>
</html>
