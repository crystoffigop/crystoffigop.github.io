<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Crystoff | Video Editor</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; background: #111; color: #eee; scroll-behavior: smooth; }
    section { min-height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; padding: 40px; }
    h1, h2 { color: #f39c12; margin-bottom: 20px; }
    nav { position: fixed; top: 20px; right: 20px; }
    nav a { color: #eee; margin: 0 10px; text-decoration: none; font-weight: bold; }
    nav a:hover { color: #f39c12; }
    .btn { display: inline-block; padding: 10px 20px; margin: 10px; border: 2px solid #f39c12; color: #f39c12; border-radius: 5px; text-decoration: none; }
    .btn:hover { background: #f39c12; color: #111; }
    video, iframe { width: 70%; max-width: 700px; margin: 20px auto; border-radius: 10px; }
    footer { padding: 20px; text-align: center; background: #222; }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Me</a>
    <a href="#works">My Works</a>
    <a href="#socials">Socials</a>
  </nav>

  <!-- Section 1: Home -->
  <section id="home">
    <h1>Hi, I'm Crystoff</h1>
    <p>Video Editor | AMVs & More</p>
    <div>
      <a class="btn" href="#about">About Me</a>
      <a class="btn" href="#works">My Works</a>
      <a class="btn" href="#socials">Socials</a>
    </div>
  </section>

  <!-- Section 2: About -->
  <section id="about">
    <h2>About Me</h2>
    <p>I'm Crystoff! I specialize in video editing. While I mainly edit anime, I also work on different fields such as IRL editing.</p>
    <p>My skills in editing anime translate directly to IRL editing.</p>
    <p>Tools: After Effects | Experience: 1 year</p>
  </section>

  <!-- Section 3: Works -->
  <section id="works">
    <h2>My Works / Edits</h2>
    <!-- Example YouTube embeds -->
    <iframe width="560" height="315" 
      src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
      frameborder="0" allowfullscreen>
    </iframe>

    <iframe width="560" height="315" 
      src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
      frameborder="0" allowfullscreen>
    </iframe>
  </section>

  <!-- Section 4: Socials -->
  <section id="socials">
    <h2>My Socials</h2>
    <p>Follow me on TikTok:</p>
    <a class="btn" href="https://www.tiktok.com/@crystoff.ftw" target="_blank">@crystoff.ftw</a>
  </section>

  <footer>
    <p>© 2025 Crystoff. All rights reserved.</p>
  </footer>

</body>
</html>
