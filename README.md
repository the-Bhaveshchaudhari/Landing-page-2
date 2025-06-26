<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Colorful Landing Page</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      line-height: 1.6;
      background: #f3f4f6;
      color: #333;
    }

    header {
      background: linear-gradient(90deg, #4facfe, #00f2fe);
      color: white;
      padding: 30px 20px;
      text-align: center;
    }

    nav {
      background: #222;
      color: white;
      padding: 15px;
      display: flex;
      justify-content: center;
      gap: 30px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1607746882042-944635dfe10e') no-repeat center center/cover;
      padding: 120px 20px;
      text-align: center;
      color: white;
    }

    .hero h1 {
      font-size: 3rem;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.4);
    }

    .features {
      display: flex;
      justify-content: space-around;
      background: linear-gradient(90deg, #43e97b, #38f9d7);
      color: white;
      padding: 50px 20px;
      text-align: center;
    }

    .features div {
      max-width: 300px;
    }

    .about {
      padding: 50px 20px;
      background: #fff;
      display: flex;
      align-items: center;
      gap: 30px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .about img {
      width: 250px;
      border-radius: 12px;
    }

    .services {
      padding: 50px 20px;
      background: #fef3c7;
      text-align: center;
    }

    .services h2 {
      margin-bottom: 30px;
    }

    .service-cards {
      display: flex;
      justify-content: center;
      gap: 25px;
      flex-wrap: wrap;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      max-width: 220px;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-10px);
    }

    .card img {
      width: 100%;
      border-radius: 8px;
    }

    .buttons {
      margin-top: 20px;
    }

    .btn {
      background-color: #4facfe;
      color: white;
      border: none;
      padding: 10px 20px;
      margin: 10px;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 25px;
    }
  </style>
</head>

<body>
  <header>
    <h1>Landing Page Project</h1>
    <p>Creative and Colorful Web Design</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h1>Build Beautiful Landing Pages</h1>
    <p>Unleash your creativity and master HTML & CSS</p>
    <div class="buttons">
      <a href="#about" class="btn">Learn About Us</a>
      <a href="#contact" class="btn">Contact Us</a>
    </div>
  </section>

  <section class="features">
    <div>
      <h3>🎯 Alignments</h3>
      <p>Learn how to align sections and elements perfectly.</p>
    </div>
    <div>
      <h3>🎨 Color Palettes</h3>
      <p>Choose vibrant and user-friendly color schemes.</p>
    </div>
    <div>
      <h3>📦 Sections & Boxes</h3>
      <p>Divide your content meaningfully and creatively.</p>
    </div>
  </section>

  <section class="about" id="about">
    <img src="https://images.unsplash.com/photo-1517245386807-bb43f82c33c4" alt="About">
    <div>
      <h2>About This Project</h2>
      <p>This landing page project is perfect for beginners. You'll apply HTML and CSS to build a structured and visually attractive webpage, enhancing your creativity and technical skills.</p>
    </div>
  </section>

  <section class="services" id="services">
    <h2>Our Services</h2>
    <div class="service-cards">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1581092795360-9b6c48d6614e" alt="User Experience">
        <p>User Experience</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1503676260728-1c00da094a0b" alt="Creative Design">
        <p>Creative Design</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c" alt="Retina Ready">
        <p>Retina Ready</p>
      </div>
    </div>
  </section>

  <section class="contact" id="contact" style="padding: 50px 20px; text-align: center; background: #e0f7fa;">
    <h2>Contact Us</h2>
    <p>Email: info@example.com</p>
    <p>Phone: +123 456 7890</p>
    <p>Address: 123 Web Street, Internet City</p>
  </section>

  <footer>
    <p>&copy; 2025 Colorful Landing Page. All rights reserved.</p>
  </footer>
</body>

</html>


