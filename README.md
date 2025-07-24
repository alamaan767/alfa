# alfa
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ALFA | Company Website</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="logo">ALFA</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Welcome to ALFA</h1>
    <p>Your trusted partner for business excellence</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>ALFA is a leading company providing high-quality solutions to businesses worldwide. We focus on innovation, client satisfaction, and integrity.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul class="service-list">
      <li>Consulting & Strategy</li>
      <li>Software Development</li>
      <li>Digital Marketing</li>
      <li>Support & Maintenance</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form id="contactForm">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <p id="formMessage"></p>
  </section>

  <footer>
    <p>&copy; 2025 ALFA. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
