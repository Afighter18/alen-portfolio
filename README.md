<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Alen Mathew – Portfolio</title>
  <style>
    body, html {margin:0; padding:0; height:100%; font-family: Arial, sans-serif;}
    .hero {
      background: url('YOUR_IMAGE_URL') center/cover no-repeat;
      height: 100vh; position: relative;
    }
    .overlay {
      position:absolute; top:0; left:0; width:100%; height:100%;
      background: rgba(0,0,0,0.6);
    }
    .hero-text {
      position:relative; z-index:1;
      top:50%; transform:translateY(-50%);
      text-align:center; color:#fff; padding:0 20px;
    }
    @keyframes flydown {
      from {transform:translateY(-100px); opacity:0;}
      to {transform:translateY(0); opacity:1;}
    }
    .hero-text h1 {
      font-size:3em; animation:flydown 2s ease-out;
    }
    section {padding:40px 20px; background:#222; color:#fff;}
    section h2 {color:#80dfff;}
    a {color:#80dfff; text-decoration:none;}
    iframe {display:block; margin:20px auto; width:90%; max-width:600px; height:340px;}
    footer {text-align:center; padding:20px; background:#111; color:#fff;}
  </style>
</head>
<body>

  <div class="hero">
    <div class="overlay"></div>
    <div class="hero-text">
      <h1>Alen Mathew</h1>
      <p>MTVHSS Student & YIP Innovator</p>
    </div>
  </div>

  <section>
    <h2>🎓 About Me</h2>
    <p>I’m Alen, a proud Class XI student at MTVHSS, Kunnam. Passionate about tech and innovation, this site shows a bit of my journey.</p>
  </section>

  <section>
    <h2>🏫 School Memories</h2>
    <iframe src="https://www.youtube.com/embed/Sug1rXRE9OY" allowfullscreen></iframe>
    <p>From coding to NSS & YIP — MTVHSS shaped my path.</p>
  </section>

  <footer>© 2025 Alen Mathew | Made with ❤️ at MTVHSS</footer>
</body>
</html>
