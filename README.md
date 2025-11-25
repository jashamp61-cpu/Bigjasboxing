<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BigJasBoxing | Jasmine Hampton</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background:#111; color:#fff; }
    header { background:#000; padding:40px 20px; text-align:center; }
    header h1 { font-size:48px; margin:0; color:#e91e63; }
    nav { background:#222; padding:10px 0; text-align:center; }
    nav a { color:#fff; margin:0 15px; text-decoration:none; font-weight:bold; }
    section { padding:40px 20px; max-width:900px; margin:auto; }
    h2 { color:#e91e63; }
    .packages { display:flex; flex-wrap:wrap; gap:20px; }
    .card { background:#1a1a1a; padding:20px; border-radius:10px; flex:1; min-width:250px; }
    .contact { background:#000; padding:40px 20px; text-align:center; }
    footer { background:#111; text-align:center; padding:20px; color:#888; }
    button { background:#e91e63; border:none; padding:12px 20px; color:#fff; font-size:16px; border-radius:6px; cursor:pointer; }
  </style>
</head>
<body>
  <header>
    <h1>BigJasBoxing</h1>
    <p>Jasmine Hampton | 12x National Champion | Olympic Trials Bronze Medalist</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#sponsorship">Sponsorship</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Jasmine</h2>
    <p>
      My name is Jasmine Hampton, born and raised in Ann Arbor, MI. I'm a 12x National Champion,
      Olympic Trials Bronze Medalist, and a future World Champion. I represent determination,
      discipline, and community pride. Your sponsorship directly supports my training, travel,
      nutrition, and gym expenses — helping me stay focused on my craft and represent Michigan
      on the national and professional stage.
    </p>
  </section>

  <section id="sponsorship">
    <h2>Sponsorship Packages</h2>
    <div class="packages">
      <div class="card">
        <h3>Silver Champion — $250/mo</h3>
        <ul>
          <li>Monthly social media thank-you + tag</li>
          <li>Business name/logo on digital materials</li>
          <li>Exclusive training updates</li>
        </ul>
      </div>
      <div class="card">
        <h3>Gold Champion — $500/mo</h3>
        <ul>
          <li>All Silver benefits</li>
          <li>Logo placement on warm-up shirts</li>
          <li>Sponsor highlight post + story</li>
          <li>1 ticket to next local fight</li>
        </ul>
      </div>
      <div class="card">
        <h3>Elite Champion — $1,000+/mo</h3>
        <ul>
          <li>All Gold benefits</li>
          <li>Logo on fight trunks or banner</li>
          <li>Media interview recognition</li>
          <li>Appearance or community event collab</li>
          <li>2 fight tickets</li>
        </ul>
      </div>
    </div>

    <br />
    <button onclick="window.location.href='Jasmine_Hampton_Sponsorship_Sheet_Final.pdf'">Download Sponsorship Sheet</button>
  </section>

  <section id="videos">
    <h2>Fight Videos</h2>
    <p>Here are two featured fight videos:</p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=3Hp7sURpZT8" target="_blank">Jasmine Hampton vs Midajah Rogers (Full Fight)</a></li>
      <li><a href="https://www.youtube.com/watch?v=Wy_VfVAgVQc" target="_blank">Jasmine Hampton – First Fight & First Knockdown</a></li>
    </ul>
  </section>

  <section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Email: <strong>jashamp61@gmail.com</strong></p>
    <p>Phone: <strong>734-717-4752</strong></p>
    <p>Location: Ann Arbor, Michigan</p>
  </section>

  <footer>
    © 2025 BigJasBoxing — All Rights Reserved
  </footer>
</body>
</html>

