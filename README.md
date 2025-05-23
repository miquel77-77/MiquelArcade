<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MiquelArcade - Juegos Online</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #111;
      color: #fff;
      text-align: center;
    }
    header {
      background-color: #222;
      padding: 1.5rem;
    }
    header h1 {
      color: #00ff99;
    }
    main {
      padding: 2rem;
    }
    .juegos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      margin-top: 2rem;
    }
    .juego {
      background-color: #1a1a1a;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,255,153,0.3);
    }
    .juego img {
      width: 100%;
      border-radius: 5px;
    }
    footer {
      background-color: #222;
      padding: 1rem;
      margin-top: 3rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>MiquelArcade</h1>
    <p>Tu sitio para juegos online y noticias gamer</p>
  </header>
  <main>
    <h2>Top Juegos</h2>
    <div class="juegos">
      <div class="juego">
        <img src="https://via.placeholder.com/300x200?text=Zelda" alt="Zelda">
        <h3>Zelda: Breath of the Wild</h3>
      </div>
      <div class="juego">
        <img src="https://via.placeholder.com/300x200?text=Elden+Ring" alt="Elden Ring">
        <h3>Elden Ring</h3>
      </div>
      <div class="juego">
        <img src="https://via.placeholder.com/300x200?text=God+of+War" alt="God of War">
        <h3>God of War Ragnarök</h3>
      </div>
    </div>
  </main>
  <footer>
    <p>&copy; 2025 MiquelArcade - Todos los derechos reservados.</p>
  </footer>
</body>
</html>
