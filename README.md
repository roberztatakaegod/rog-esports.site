<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ROG Esports</title>
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #0a0a0a;
      color: #f0f0f0;
    }
    header {
      background: #111;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    header h1 {
      margin: 0;
      color: #e00;
    }
    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      gap: 1rem;
    }
    nav a {
      color: #f0f0f0;
      text-decoration: none;
    }
    .hero {
      text-align: center;
      padding: 4rem 1rem;
      background:
        linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
        url('https://wallpapers.com/images/hd/herobrine-minecraft-pictures-1280-x-720-u5e3bozcsb99y0i9.jpg') center/cover no-repeat;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin: 0;
      color: #ff0;
    }
    .hero p {
      font-size: 1.2rem;
    }
    .stats {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background: #111;
      padding: 2rem 0;
    }
    .stat {
      text-align: center;
    }
    .stat h3 {
      margin: 0;
      font-size: 2rem;
      color: #e00;
    }
    section {
      padding: 2rem 1rem;
    }
    h2 {
      text-align: center;
      color: #e00;
    }
    p {
      max-width: 800px;
      margin: 1rem auto;
      text-align: center;
    }
    .contact a {
      color: #4ea6ff;
      text-decoration: underline;
    }
    footer {
      background: #111;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>ROG Esports</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#tournaments">Tournaments</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Welcome to ROG Esports</h2>
    <p>Where gaming meets epic Minecraft battles.</p>
  </section>

  <section class="stats">
    <div class="stat"><h3>500+</h3><p>Registrations</p></div>
    <div class="stat"><h3>1M+</h3><p>Impressions</p></div>
    <div class="stat"><h3>300K</h3><p>Peak Viewership</p></div>
  </section>

  <section id="tournaments">
    <h2>Tournaments</h2>
    <p>No tournaments for now.<br>
    Join our Discord for future updates:</p>
    <p><a href="https://discord.gg/6UX7QNbpCe" target="_blank">https://discord.gg/6UX7QNbpCe</a></p>
  </section>

  <section id="about">
    <h2>About ROG Esports</h2>
    <p>ROG Esports is more than just tournaments — it’s a movement. We empower gamers across India with unforgettable competitions, top-tier experiences, and a community that thrives on passion, performance, and play. Whether you're a rising star or a pro, we have a place for you.</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Email us at: <a href="mailto:hustlewithroberz@gmail.com">hustlewithroberz@gmail.com</a></p>
    <p>Join our Discord: <a href="https://discord.gg/6UX7QNbpCe" target="_blank">https://discord.gg/6UX7QNbpCe</a></p>
  </section>

  <footer>
    &copy; 2025 ROG Esports. All Rights Reserved.
  </footer>

</body>
</html>
