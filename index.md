<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <title>HackMe School</title>
  <style>
    body {
      background-color: black;
      color: #00ff00;
      font-family: monospace;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100vh;
      margin: 0;
    }
    h1 {
      font-size: 4em;
      text-align: center;
      margin-bottom: 30px;
      animation: blink 1s infinite;
    }
    @keyframes blink {
      50% { opacity: 0; }
    }
    p {
      margin-bottom: 40px;
      font-size: 1.5em;
    }
    .levels a {
      display: block;
      margin: 15px;
      color: #00ff00;
      text-decoration: none;
      font-size: 1.5em;
      transition: all 0.3s ease;
    }
    .levels a:hover {
      color: #ff0000;
      transform: scale(1.2);
      text-shadow: 0 0 10px #ff0000;
    }
  </style>
</head>
<body>
  <h1 id="title">HACKME SCHOOL</h1>
  <p>Wybierz poziom i sprawdź swoje umiejętności</p>

  <div class="levels">
    <a href="level1.html">Level 1 – Hasło w kodzie</a>
    <a href="level2.html">Level 2 – Łatwe podstrony</a>
    <a href="level3.html">Level 3 – Słabe hasła</a>
    <a href="level4.html">Level 4 – Plik konfiguracyjny</a>
    <a href="level5.html">Level 5 – Dane w URL</a>
    <a href="level6.html">Level 6 – Brute Force</a>
  </div>

  <script>
    // Migający losowo kolorowy tytuł
    const title = document.getElementById("title");
    function randomColor() {
      const colors = ["#00ff00", "#ff0000", "#00ffff", "#ffff00", "#ff00ff", "#ffffff"];
      return colors[Math.floor(Math.random() * colors.length)];
    }
    setInterval(() => {
      title.style.color = randomColor();
      title.style.textShadow = `0 0 20px ${randomColor()}`;
    }, 500);
  </script>
</body>
</html>
