<!DOCTYPE html>
<html lang="lt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TheHairFire – Julija, plaukų stilistė</title>
  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #f3f2ef;
      color: #1e1e1e;
    }

    header {
      background-color: #e5e4e1;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      letter-spacing: 1px;
    }

    nav {
      background-color: #dcdad7;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 15px;
    }

    nav a {
      text-decoration: none;
      color: #1e1e1e;
      font-weight: bold;
      text-transform: uppercase;
      font-size: 0.9em;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: 0 auto;
    }

    h2 {
      border-bottom: 1px solid #ccc;
      padding-bottom: 10px;
      margin-bottom: 30px;
    }

    .portfolio img {
      width: 100%;
      max-width: 300px;
      margin: 10px;
      border-radius: 8px;
      object-fit: cover;
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #aaa;
      border-radius: 5px;
    }

    .contact-form button {
      background-color: #1e1e1e;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    footer {
      background-color: #e5e4e1;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }

    .instagram-carousel {
      display: flex;
      overflow-x: auto;
      gap: 10px;
      padding: 20px 0;
    }

    .instagram-carousel img {
      width: 200px;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      flex-shrink: 0;
    }
  </style>
</head>
<body>

  <header>
    <h1>TheHairFire</h1>
    <p>Julija – plaukų stilistė su daugiau nei 7 metų patirtimi</p>
  </header>

  <nav>
    <a href="#apie">Apie mane</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#blogas">Blogas</a>
    <a href="#produktai">Produktai</a>
    <a href="#rezervacija">Rezervacija</a>
    <a href="#kontaktai">Kontaktai</a>
  </nav>

  <section id="apie">
    <h2>Apie mane</h2>
    <p>Esu Julija – plaukų stilistė su daugiau nei 7 metų patirtimi. Myliu savo darbą ir įkvepiuosi kiekvienu klientu. Nuolat mokausi, seku tendencijas ir siekiu estetikos kiekviename įvaizdyje.</p>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio">
      <img src="https://via.placeholder.com/300x400" alt="Šukuosenos pavyzdys" />
      <img src="https://via.placeholder.com/300x400" alt="Šukuosenos pavyzdys" />
    </div>
  </section>

  <section id="blogas">
    <h2>Blogas</h2>
    <p>Čia netrukus atsiras mano straipsniai, patarimai apie plaukų priežiūrą ir įkvėpimo šaltiniai.</p>
  </section>

  <section id="produktai">
    <h2>Plaukų produktai</h2>
    <p>Čia galėsite įsigyti mano mėgstamus plaukų priežiūros ir formavimo produktus.</p>
  </section>

  <section id="rezervacija">
    <h2>Rezervacija</h2>
    <p>Rezervuokite laiką pas mane per šią nuorodą:</p>
    <a href="https://t.me/yourusername" target="_blank">Rašyti į Telegram</a>
  </section>

  <section id="kontaktai">
    <h2>Kontaktai</h2>
    <form class="contact-form">
      <input type="text" placeholder="Jūsų vardas" required />
      <input type="email" placeholder="Jūsų el. paštas" required />
      <textarea placeholder="Jūsų žinutė" rows="5" required></textarea>
      <button type="submit">Siųsti</button>
    </form>
  </section>

  <section id="instagram">
    <h2>Instagram</h2>
    <div class="instagram-carousel">
      <!-- Pakeisk paveikslėlių nuorodas tikrais iš Instagram -->
      <img src="https://via.placeholder.com/200" alt="Instagram 1" />
      <img src="https://via.placeholder.com/200" alt="Instagram 2" />
      <img src="https://via.placeholder.com/200" alt="Instagram 3" />
      <img src="https://via.placeholder.com/200" alt="Instagram 4" />
    </div>
    <p style="text-align: center;"><a href="https://instagram.com/tavo_paskyra" target="_blank">Sekite mane Instagram</a></p>
  </section>

  <footer>
    © 2025 TheHairFire – Julija, plaukų stilistė
  </footer>

</body>
</html>
