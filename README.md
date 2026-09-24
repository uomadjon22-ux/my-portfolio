<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shaxsiy Portfolio | Veb-Dasturchi</title>
  <link rel="stylesheet" href="style.css">
  <!-- Font Awesome ikonkalari uchun -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>

  <!-- Navigatsiya paneli -->
  <header class="navbar">
    <div class="logo">DevPortfolio<span>.</span></div>
    <nav>
      <ul class="nav-links">
        <li><a href="#about">Men haqimda</a></li>
        <li><a href="#skills">Ko'nikmalar</a></li>
        <li><a href="#projects">Loyihalar</a></li>
        <li><a href="#contact">Aloqa</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Bo'limi -->
  <section class="hero" id="about">
    <div class="hero-content">
      <p class="greeting">Salom, men</p>
      <h1>Sobirjon Umarov</h1>
      <h2>Frontend Veb-Dasturchi</h2>
      <p class="description">
        Zamonaviy, moslashuvchan hamda foydalanuvchilar uchun qulay veb-saytlar va ilovalar yarataman.
      </p>
      <div class="hero-btns">
        <a href="#projects" class="btn primary-btn">Loyihalarim</a>
        <a href="#contact" class="btn secondary-btn">Bog'lanish</a>
      </div>
    </div>
  </section>

  <!-- Ko'nikmalar (Skills) Bo'limi -->
  <section class="skills-section" id="skills">
    <h2 class="section-title">Ko'nikmalarim</h2>
    <div class="skills-grid">
      <div class="skill-card">
        <i class="fa-brands fa-html5"></i>
        <h3>HTML5</h3>
        <p>Semantik va to'g'ri struktura</p>
      </div>
      <div class="skill-card">
        <i class="fa-brands fa-css3-alt"></i>
        <h3>CSS3 / SASS</h3>
        <p>Flexbox, Grid, Animatsiyalar</p>
      </div>
      <div class="skill-card">
        <i class="fa-brands fa-js"></i>
        <h3>JavaScript</h3>
        <p>ES6+, DOM dinamikasi, API</p>
      </div>
      <div class="skill-card">
        <i class="fa-brands fa-git-alt"></i>
        <h3>Git & GitHub</h3>
        <p>Kodni boshqarish va versiyalash</p>
      </div>
    </div>
  </section>

  <!-- Loyihalar Bo'limi -->
  <section class="projects-section" id="projects">
    <h2 class="section-title">Mening Loyihalarim</h2>
    <div class="projects-grid">
      <!-- 1-Loyiha -->
      <div class="project-card">
        <div class="project-info">
          <h3>Internet Do'kon Veb-Sayti</h3>
          <p>HTML, CSS va JS yordamida yaratilgan e-tijorat loyihasi. Savatcha va filter funksiyalari mavjud.</p>
          <div class="tags">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
          </div>
          <a href="#" class="project-link">Ko'rish <i class="fa-solid fa-arrow-right"></i></a>
        </div>
      </div>
      <!-- 2-Loyiha -->
      <div class="project-card">
        <div class="project-info">
          <h3>Ob-Havo Ilovasi</h3>
          <p>Real vaqt rejimida ob-havo ma'lumotlarini taqdim etuvchi veb-ilova (OpenWeather API integrated).</p>
          <div class="tags">
            <span>JavaScript</span>
            <span>REST API</span>
            <span>CSS</span>
          </div>
          <a href="#" class="project-link">Ko'rish <i class="fa-solid fa-arrow-right"></i></a>
        </div>
      </div>
    </div>
  </section>

  <!-- Aloqa Bo'limi -->
  <section class="contact-section" id="contact">
    <h2 class="section-title">Men bilan bog'laning</h2>
    <form class="contact-form" id="contactForm">
      <div class="input-group">
        <input type="text" placeholder="Ismingiz" required>
        <input type="email" placeholder="Elektron pochtangiz" required>
      </div>
      <textarea rows="5" placeholder="Xabaringiz..." required></textarea>
      <button type="submit" class="btn primary-btn">Xabarni yuborish</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Sobirjon Umarov. Barcha huquqlar himoyalangan.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
