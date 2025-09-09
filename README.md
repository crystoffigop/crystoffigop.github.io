<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Crystoff | Video Editor</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; background: #111; color: #eee; scroll-behavior: smooth; }
    section { min-height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; padding: 40px; text-align: center; }
    h1, h2, h3 { color: #f39c12; margin-bottom: 20px; }
    p { max-width: 700px; line-height: 1.6; margin-bottom: 15px; }
    nav { position: fixed; top: 20px; right: 20px; }
    nav a { color: #eee; margin: 0 10px; text-decoration: none; font-weight: bold; }
    nav a:hover { color: #f39c12; }
    .btn { display: inline-block; padding: 10px 20px; margin: 10px; border: 2px solid #f39c12; color: #f39c12; border-radius: 5px; text-decoration: none; }
    .btn:hover { background: #f39c12; color: #111; }
    .video-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); gap: 20px; width: 100%; max-width: 1200px; }
    iframe { width: 100%; aspect-ratio: 16 / 9; border-radius: 10px; }
    footer { padding: 20px; text-align: center; background: #222; }
    .works-subsection { margin-top: 40px; width: 100%; }
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
    <p>Video Editor | AMVs & Creative Media</p>
    <div>
      <a class="btn" href="#about">About Me</a>
      <a class="btn" href="#works">My Works</a>
      <a class="btn" href="#socials">Socials</a>
    </div>
  </section>

  <!-- Section 2: About -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I’m Crystoff, a video editor with a passion for bringing stories to life through visuals and music. While I specialize in anime music videos (AMVs), I also edit real-life content and other creative projects.</p>
    <p>The skills I’ve honed in anime editing—timing, pacing, and visual storytelling—translate directly into live-action and other editing fields. My main tool is <strong>Adobe After Effects</strong>, and I’ve been actively editing for over a year.</p>
  </section>

  <!-- Section 3: Works -->
  <section id="works">
    <h2>My Works</h2>

    <!-- AMVs -->
    <div class="works-subsection">
      <h3>Anime Music Videos (AMVs)</h3>
      <div class="video-grid">
        <!-- AMV 1 -->
        <iframe src="https://www.youtube.com/embed/F2fqxjkD3kU" frameborder="0" allowfullscreen></iframe>
        <!-- AMV 2 -->
        <iframe src="https://www.youtube.com/embed/S5AKyKJ8O7g" frameborder="0" allowfullscreen></iframe>
        <!-- AMV 3 -->
        <iframe src="https://www.youtube.com/embed/PM-jjr5xSHs" frameborder="0" allowfullscreen></iframe>
        <!-- AMV 4 -->
        <iframe src="https://www.youtube.com/embed/4Vd-DuBWI2U" frameborder="0" allowfullscreen></iframe>
        <!-- AMV 5 -->
        <iframe src="https://www.youtube.com/embed/uJEUxqZIgQY" frameborder="0" allowfullscreen></iframe>
        <!-- AMV 6 -->
        <iframe src="https://www.youtube.com/embed/BDgWQErYuRc" frameborder="0" allowfullscreen></iframe>
        <!-- AMV 7 -->
        <iframe src="https://www.youtube.com/embed/1DL65sYs6qI" frameborder="0" allowfullscreen></iframe>
        <!-- AMV 8 -->
        <iframe src="https://www.youtube.com/embed/BVse-fHPGpI" frameborder="0" allowfullscreen></iframe>
        <!-- AMV 9 -->
        <iframe src="https://www.youtube.com/embed/RTU5WHLTSA0" frameborder="0" allowfullscreen></iframe>
        <!-- AMV 10 -->
        <iframe src="https://www.youtube.com/embed/XnAfHOiMg5Q" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>

    <!-- Placeholder for MMVs -->
    <div class="works-subsection">
      <h3>Manga Animation Edits (MMVs)</h3>
      <p>(Coming soon — still uploading! 🚀)</p>
    </div>
  </section>

  <!-- Section 4: Socials -->
  <section id="socials">
    <h2>Connect With Me</h2>
    <p>Check out my content and follow me on TikTok:</p>
    <a class="btn" href="https://www.tiktok.com/@crystoff.ftw" target="_blank">@crystoff.ftw</a>
  </section>

  <footer>
    <p>© 2025 Crystoff. All rights reserved.</p>
  </footer>

</body>
</html>
