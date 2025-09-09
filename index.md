<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <title>HackMe School</title>
  <style>
    body {
      background-color: #0a1a3f;
      color: #f0f0f0;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100vh;
      margin: 0;
    }
    h1 {
      font-size: 6em; /* dużo większy tytuł */
      text-align: center;
      margin-bottom: 50px;
      color: #ffffff;
    }
    p {
      margin-bottom: 50px;
      font-size: 2em; /* większy podtytuł */
      color: #cccccc;
    }
    .levels {
      display: flex;
      flex-direction: column;
      gap: 30px;
    }
    .levels a {
      background: #1e2a55;
      padding: 25px 50px; /* większe przyciski */
      border-radius: 16px;
      color: #ffffff;
      text-decoration: none;
      font-size: 2em; /* większa czcionka */
      transition: all 0.3s ease;
      box-shadow: 0 6px 12px rgba(0,0,0,0.6);
    }
    .levels a:hover {
      background: #4da6ff;
      transform: scale(1.1);
      box-shadow: 0 8px 18px rgba(0,0,0,0.7);
    }
  </style>
</head>
<body>
  <h1>HackMe School</h1>
  <p>Wybierz poziom i sprawdź swoje umiejętności</p>

  <div class="levels">
    <a href="level1.html">Level 1 – Hasło w kodzie</a>
    <a href="level2.html">Level 2 – Łatwe podstrony</a>
    <a href="level3.html">Level 3 – Słabe hasła</a>
    <a href="level4.html">Level 4 – Plik konfiguracyjny</a>
    <a href="level5.html">Level 5 – Dane w URL</a>
    <a href="level6.html">Level 6 – Brute Force</a>
  </div>
</body>
</html>
