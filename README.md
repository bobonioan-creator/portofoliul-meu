<!DOCTYPE html>

<html lang="ro">

<head>

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Portofoliul lui Călin</title>

<style>
  /* SECTIUNEA CE STIU */

#abilitati {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 70px 30px;
}

#abilitati h2 {
    margin-bottom: 35px;
}

.abilitati-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
    width: 100%;
}

.abilitate-card {
    width: 100%;
    min-height: 250px;
    padding: 30px;
    background: #1b2242;
    border: 1px solid #30385f;
    border-radius: 16px;
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.abilitate-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 15px 30px rgba(140, 162, 255, 0.2);
}

  /* ABILITĂȚI */

.abilitati-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin-top: 30px;
}

.abilitate-card {
  background: #1b2242;
  border: 1px solid #30385f;
  border-radius: 16px;
  padding: 25px;
  text-align: center;
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.25);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.abilitate-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 15px 35px rgba(140, 162, 255, 0.2);
}

.abilitate-icon {
  font-size: 35px;
  margin-bottom: 10px;
}

.abilitate-card h3 {
  color: #ffffff;
  margin: 10px 0;
}

.abilitate-card p {
  color: #c8cdea;
  min-height: 50px;
}

.abilitate-card span {
  display: block;
  margin-top: 8px;
  color: #9c7cff;
  font-weight: bold;
}

/* BARE DE PROGRES */

.bara {
  width: 100%;
  height: 9px;
  background: #101426;
  border-radius: 10px;
  overflow: hidden;
  margin-top: 20px;
}

.progres {
  height: 100%;
  border-radius: 10px;
  background: linear-gradient(90deg, #7461e8, #9c7cff);
  animation: progresAnimatie 1.2s ease-out;
}

.html-progres {
  width: 80%;
}

.css-progres {
  width: 70%;
}

.js-progres {
  width: 50%;
}
@media (max-width: 800px) {
    .abilitati-container {
        grid-template-columns: 1fr;
    }
}

@keyframes progresAnimatie {
  from {
    width: 0;
  }
}
  /* CARD DESPRE MINE */

.despre-card {
  background: #1b2242;
  border: 1px solid #30385f;
  border-radius: 16px;
  padding: 35px;
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.25);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.despre-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 18px 40px rgba(140, 162, 255, 0.2);
}

.despre-card h2 {
  margin-top: 0;
  margin-bottom: 18px;
}

.despre-card p {
  color: #c8cdea;
  font-size: 17px;
}
  /* DESPRE MINE */

.despre-card {
  background: #1b2242;
  border-radius: 12px;
  padding: 30px;
  border: 1px solid #30385f;
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.2);
  max-width: 700px;
}

.despre-card h2 {
  margin-top: 0;
}

.despre-card p {
  color: #c8cdea;
}
  /* MESAJ DE SUCCES */

.mesaj-succes {
  display: none;
  max-width: 650px;
  margin-top: 30px;
  padding: 40px 30px;
  text-align: center;
  background: #1b2242;
  border: 1px solid #30385f;
  border-radius: 16px;
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.25);
}

.bifa {
  width: 70px;
  height: 70px;
  margin: 0 auto 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background: #7461e8;
  color: white;
  font-size: 40px;
  font-weight: bold;
}

.mesaj-succes h3 {
  font-size: 26px;
  margin-bottom: 10px;
  color: #ffffff;
}

.mesaj-succes p {
  color: #b8c0e0;
  margin-bottom: 25px;
}

.mesaj-succes.activ {
  display: block;
  animation: fadeInUp 0.5s ease-out;
}
/* ANIMATII */
@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }

  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.hero img {
  animation: fadeInUp 0.8s ease-out;
}

.hero > div {
  animation: fadeInUp 0.8s ease-out;
}

section {
  animation: fadeInUp 0.8s ease-out;
}

.card {
  animation: fadeInUp 0.8s ease-out;
}
    
    section {
  width: 100%;
  max-width: 1400px;
  margin: auto;
  padding: 65px 60px;
}

    h2 {
      color: #9c7cff;
      font-size: 30px;
    }

    /* PROIECTE */

.proiecte {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 20px;
}

.card {
  background: #1b2242;
  border-radius: 12px;
  padding: 22px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  animation: cardAppear 0.8s ease-out both;
}

.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 12px 30px rgba(140, 162, 255, 0.25);
}

.card h3 {
  color: #ffffff;
  margin-top: 0;
}

.card p {
  color: #c8cdea;
}

.card:nth-child(1) {
  animation-delay: 0.2s;
}

.card:nth-child(2) {
  animation-delay: 0.4s;
}

.card:nth-child(3) {
  animation-delay: 0.6s;
}

@keyframes cardAppear {
  from {
    opacity: 0;
    transform: translateY(40px);
  }

  to {
    opacity: 1;
    transform: translateY(0);
  }
}
/* FORMULAR DE CONTACT */

.formular-contact {
  max-width: 650px;
  margin-top: 30px;
  padding: 30px;
  background: #1b2242;
  border: 1px solid #30385f;
  border-radius: 16px;
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.25);
}

.camp {
  margin-bottom: 20px;
}

.camp label {
  display: block;
  margin-bottom: 8px;
  color: #ffffff;
  font-weight: bold;
}

.camp input,
.camp textarea {
  width: 100%;
  padding: 14px;
  background: #101426;
  color: #ffffff;
  border: 2px solid #30385f;
  border-radius: 9px;
  font-family: Arial, sans-serif;
  font-size: 15px;
  outline: none;
  transition: 0.3s;
}

.camp input:focus,
.camp textarea:focus {
  border-color: #8ca2ff;
  box-shadow: 0 0 12px rgba(140, 162, 255, 0.2);
}

.camp textarea {
  resize: vertical;
}

.camp input::placeholder,
.camp textarea::placeholder {
  color: #7f87a8;
}

.formular-contact .buton {
  border: none;
  cursor: pointer;
  transition: 0.3s;
}

.formular-contact .buton:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(116, 97, 232, 0.3);
}

.contact-github {
  margin-top: 30px;
}
  </style>


  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background: #101426;
      color: #f4f6ff;
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    header {
      background: #171d38;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 10%;
    }

    .logo {
      color: #8ca2ff;
      font-size: 24px;
      font-weight: bold;
    }

    nav a {
      color: white;
      margin-left: 18px;
      text-decoration: none;
    }

    nav a:hover {
      color: #8ca2ff;
    }

    .hero {
  max-width: 1400px;
  margin: auto;
  min-height: 470px;
  display: flex;
  align-items: center;
  gap: 50px;
  padding: 70px 60px;
}

    .hero img {
  width: 230px;
  height: 230px;
  border-radius: 50%;
  border: 4px solid #8ca2ff;
  background: linear-gradient(135deg, #8ca2ff, #7461e8);
  padding: 6px;
  object-fit: cover;
  box-shadow:
    0 0 25px rgba(140, 162, 255, 0.35),
    0 0 60px rgba(116, 97, 232, 0.2);
  transition: transform 0.4s ease, box-shadow 0.4s ease;
}

.hero img:hover {
  transform: scale(1.05) rotate(2deg);
  box-shadow:
    0 0 35px rgba(140, 162, 255, 0.5),
    0 0 80px rgba(116, 97, 232, 0.3);
}

    h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    .mov {
      color: #9c7cff;
    }

    .buton {
      display: inline-block;
      background: #7461e8;
      color: white;
      border-radius: 8px;
      padding: 12px 20px;
      margin-top: 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .buton:hover {
      background: #5b48c9;
    }
    .despre-card {
    width: 100%;
    max-width: 650px;
    box-sizing: border-box;
    margin: 0 auto;
    padding: 30px;
    background: #1b2242;
    border: 1px solid #30385f;
    border-radius: 16px;
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.25);
}

.despre-card h2 {
    margin-top: 0;
    margin-bottom: 15px;
}

.despre-card p {
    color: #c8cdea;
    font-size: 16px;
    line-height: 1.8;
}
#despre {
    width: 100%;
    max-width: 1400px;
    box-sizing: border-box;
}

.despre-card {
    width: 100%;
    max-width: 900px;
    box-sizing: border-box;
    margin: 0 auto;
}
.hero {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
    align-items: start;
}

.hero > img {
    justify-self: center;
}

.hero > div {
    width: 100%;
}

#despre {
    width: 100%;
    grid-column: 1 / -1;
}

.despre-card {
    width: 100%;
    max-width: 100%;
    box-sizing: border-box;
}

#abilitati {
    width: 100%;
    grid-column: 1 / -1;
    box-sizing: border-box;
}

.abilitati-container {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.abilitate-card {
    width: 100%;
    box-sizing: border-box;
}

#abilitati {
    grid-column: 1 / -1;
    width: 100%;
    max-width: none;
    box-sizing: border-box;
}

.abilitati-container {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.abilitate-card {
    width: 100%;
    box-sizing: border-box;
}
  </style>


<body>

  <header>
    <div class="logo">Călin.dev</div>

    <nav>
      <a href="#despre">Despre mine</a>
      <a href="#proiecte">Proiecte</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>

    <section class="hero">

      <img
        src="https://api.dicebear.com/9.x/adventurer/svg?seed=Calin"
        alt="Avatarul lui Călin"
      >

      <div>
        <h1>
          Salut, sunt <span class="mov">Călin</span>.
        </h1>

        <p>
          Ofer servicii de dezvoltare web și construiesc site-uri moderne.
          Aici îmi prezint proiectele și progresul.
        </p>

        <a class="buton" href="#proiecte">
          Vezi proiectele mele
        </a>
      </div>

    <section id="despre">

  <div class="despre-card">

    <h2>Despre mine</h2>

    <p>
      Sunt Călin și ofer servicii de dezvoltare web.
      Îmi place să construiesc proiecte reale dupa preferintele voastre și
      să învăț mereu ceva nou.
    </p>

    <p>
      Îmi place să transform ideile în proiecte reale
      și să devin din ce în ce mai bun în dezvoltarea web.
    </p>

  </div>

</section>
<section id="abilitati">

  <h2>Ce știu</h2>

  <div class="abilitati-container">

    <div class="abilitate-card">
      <div class="abilitate-icon">🌐</div>
      <h3>HTML</h3>
      <p>Construiesc structura paginilor web.</p>

      <div class="bara">
        <div class="progres html-progres"></div>
      </div>
      <span>80%</span>
    </div>

    <div class="abilitate-card">
      <div class="abilitate-icon">🎨</div>
      <h3>CSS</h3>
      <p>Stilizez și creez designul paginilor.</p>

      <div class="bara">
        <div class="progres css-progres"></div>
      </div>
      <span>70%</span>
    </div>

    <div class="abilitate-card">
      <div class="abilitate-icon">⚡</div>
      <h3>JavaScript</h3>
      <p>Adaug interactivitate și funcții site-urilor.</p>

      <div class="bara">
        <div class="progres js-progres"></div>
      </div>
      <span>50%</span>
    </div>

  </div>

</section>
  </main>
<section id="despre"></section>
<section id="proiecte">

  <h2>Proiectele mele</h2>

  <div class="proiecte">

    <div class="card">
      <h3>🎨 Prima mea pagină</h3>

      <p>
        O pagină web interactivă cu butoane,
        culori și elemente dinamice.
      </p>

      <a href="https://github.com/bobonioan-creator/prima-mea-pagina"
   class="buton"
   target="_blank">
    Vezi proiectul
</a>
    </div>


    <div class="card">
      <h3>💻 Portofoliul meu</h3>

      <p>
        Site-ul meu personal în care îmi prezint
        proiectele și progresul în dezvoltarea web.
      </p>

      <a href="https://github.com/bobonioan-creator/portofoliul-meu"
   class="buton"
   target="_blank">
    Vezi proiectul
</a>
    </div>


    <div class="card">
      <h3>🚀 Următorul proiect</h3>

      <p>
        Următoarea mea idee va apărea aici.
        Voi adăuga proiecte din ce în ce mai interesante.
      </p>

      <a href="#" class="buton">
        În curând
      </a>
    </div>

  </div>
</style>
</head>


  <header>
    
  <main>
    
    

    <section id="contact">

  <h2>Hai să vorbim</h2>

  <p>
    Ai o idee de proiect sau vrei să mă contactezi?
    Completează formularul de mai jos.
  </p>

      <form
    id="formular-contact"
    class="formular-contact"
    action="https://formspree.io/f/mppzpago"
    method="POST"
  >

    <div class="camp">
      <label for="nume">Nume</label>

      <input
        type="text"
        id="nume"
        name="nume"
        placeholder="Numele tău"
        required
      >
    </div>

    <div class="camp">
      <label for="email">Email</label>

      <input
        type="email"
        id="email"
        name="email"
        placeholder="emailul-tau@example.com"
        required
      >
    </div>

    <div class="camp">
      <label for="mesaj">Mesaj</label>

      <textarea
        id="mesaj"
        name="mesaj"
        rows="6"
        placeholder="Scrie mesajul tău aici..."
        required
      ></textarea>
    </div>

    <button type="submit" class="buton">
      Trimite mesajul
    </button>

  </form>


  <div id="mesaj-succes" class="mesaj-succes">

    <div class="bifa">✓</div>

    <h3>Mulțumesc pentru mesaj! 🎉</h3>

    <p>
      Mesajul tău a fost trimis cu succes.
      Îți voi răspunde cât mai curând.
    </p>

    <button id="trimite-altul" class="buton">
      Trimite alt mesaj
    </button>

  </div>


  <div class="contact-github">

    <p>Poți vedea și proiectele mele pe GitHub:</p>

    <a
      class="buton"
      href="https://github.com/bobonioan-creator"
      target="_blank"
    >
      Vezi profilul meu GitHub
    </a>

  </div>

</section>
  </main>

  <footer>
    <p>© <span id="an"></span> Călin. Toate drepturile rezervate.</p>
  </footer>

  <script>
    document.getElementById("an").textContent = new Date().getFullYear();
  </script>
<script>
const formular = document.getElementById("formular-contact");
const mesajSucces = document.getElementById("mesaj-succes");
const trimiteAltul = document.getElementById("trimite-altul");

formular.addEventListener("submit", async function(event) {
  event.preventDefault();

  const dateFormular = new FormData(formular);

  try {
    const raspuns = await fetch(formular.action, {
      method: "POST",
      body: dateFormular,
      headers: {
        "Accept": "application/json"
      }
    });

    if (raspuns.ok) {
      formular.style.display = "none";
      mesajSucces.classList.add("activ");
      formular.reset();
    } else {
      alert("A apărut o problemă. Încearcă din nou.");
    }
  } catch (eroare) {
    alert("Nu s-a putut trimite mesajul. Verifică conexiunea la internet.");
  }
});

trimiteAltul.addEventListener("click", function() {
  mesajSucces.classList.remove("activ");
  formular.style.display = "block";
});
</script>
</html>
