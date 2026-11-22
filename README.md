
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Kelvin Monday, professionally known as KYNZO. Digital creator, video editor and creative entrepreneur from Nigeria.">
  <meta name="author" content="Kelvin Monday">
  <meta name="theme-color" content="#080808">
  <title>Kelvin Monday | KYNZO</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      background: #080808;
      color: #f5f5f5;
      font-family: Arial, sans-serif;
      line-height: 1.7;
    }
    a { color: inherit; text-decoration: none; }
    header {
      padding: 22px 8%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 1px solid #222;
    }
    .logo { font-weight: 900; letter-spacing: 3px; font-size: 21px; }
    nav { display: flex; gap: 25px; font-size: 13px; color: #aaa; }
    nav a:hover { color: white; }
    .hero {
      min-height: 75vh;
      padding: 100px 8%;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .tag { color: #999; letter-spacing: 4px; font-size: 11px; }
    h1 {
      font-size: clamp(48px, 10vw, 100px);
      line-height: 1.05;
      margin: 25px 0;
      letter-spacing: -5px;
    }
    h1 span { color: #888; }
    .intro { color: #aaa; max-width: 520px; font-size: 17px; }
    .button {
      display: inline-block;
      border: 1px solid #777;
      padding: 12px 24px;
      margin-top: 30px;
      font-size: 12px;
      letter-spacing: 2px;
    }
    .button:hover { background: white; color: black; }
    section { padding: 75px 8%; border-top: 1px solid #222; }
    .eyebrow { color: #888; letter-spacing: 3px; font-size: 11px; }
    h2 { font-size: 36px; margin: 12px 0 20px; }
    .description { color: #aaa; max-width: 650px; }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      margin-top: 30px;
    }
    .card { border: 1px solid #292929; padding: 25px; }
    .card h3 { margin-bottom: 10px; }
    .card p { color: #999; font-size: 14px; }
    .socials { display: flex; flex-wrap: wrap; gap: 25px; margin-top: 25px; }
    .socials a { color: #ccc; border-bottom: 1px solid #666; }
    footer {
      padding: 30px 8%;
      color: #777;
      font-size: 12px;
      border-top: 1px solid #222;
    }
    @media(max-width: 600px) {
      header { padding: 18px 6%; }
      nav { gap: 12px; font-size: 11px; }
      .hero, section { padding-left: 7%; padding-right: 7%; }
      h1 { letter-spacing: -3px; }
    }
  </style>
</head>
<body>
  <header>
    <a class="logo" href="#">KM.</a>
    <nav>
      <a href="#about">ABOUT</a>
      <a href="#work">WORK</a>
      <a href="#contact">CONTACT</a>
    </nav>
  </header>

  <main>
    <div class="hero">
      <p class="tag">DIGITAL CREATOR · CREATIVE ENTREPRENEUR</p>
      <h1>KELVIN<br><span>MONDAY.</span></h1>
      <p class="intro">
        Known professionally as KYNZO. Exploring creativity,
        digital storytelling and technology while building ideas
        that inspire and connect people.
      </p>
      <div>
        <a class="button" href="#about">DISCOVER MY STORY →</a>
      </div>
    </div>

    <section id="about">
      <p class="eyebrow">01 / ABOUT ME</p>
      <h2>Meet Kelvin Monday.</h2>
      <p class="description">
        I'm Kelvin Monday, a Nigerian digital creator and creative
        entrepreneur known as KYNZO. My interests include video
        editing, digital media, technology and building creative
        projects. I'm passionate about learning, creating and
        turning ideas into reality.
      </p>
    </section>

    <section id="work">
      <p class="eyebrow">02 / WHAT I DO</p>
      <h2>My Creative World.</h2>
      <div class="cards">
        <div class="card">
          <h3>Video Editing</h3>
          <p>Creative storytelling and engaging video content.</p>
        </div>
        <div class="card">
          <h3>Digital Content</h3>
          <p>Creating content and building an online community.</p>
        </div>
        <div class="card">
          <h3>Technology</h3>
          <p>Exploring web development and digital innovation.</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <p class="eyebrow">03 / CONNECT</p>
      <h2>Let's Connect.</h2>
      <p class="description">
        Follow my journey and discover what I'm creating.
      </p>
      <div class="socials">
        <a href="https://www.tiktok.com/@kynzo40" target="_blank" rel="noopener">TikTok</a>
        <a href="https://www.facebook.com/" target="_blank" rel="noopener">Facebook</a>
        <a href="https://www.instagram.com/" target="_blank" rel="noopener">Instagram</a>
      </div>
    </section>
  </main>

  <footer>
    © 2026 Kelvin Monday (KYNZO). All rights reserved.
  </footer>
</body>
</html>
