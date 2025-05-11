<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>EricPlay Games</title>
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet"/>
  <style>
    body {
      margin: 0;
      font-family: 'Press Start 2P', cursive;
      background-color: #0f0f0f;
      color: white;
    }
    header {
      background-color: #222;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      color: #00ff99;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #00ffcc;
      margin: 0 15px;
      text-decoration: none;
    }
    nav a:hover {
      color: #fff700;
    }
    .main {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 40px;
      background: linear-gradient(to bottom right, #1e1e1e, #2c2c2c);
    }
    .game {
      background-color: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px #000;
      text-align: center;
    }
    .game h3 {
      color: #00ff99;
    }
    .game a button {
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #00ffcc;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-family: 'Press Start 2P', cursive;
    }
    .game a button:hover {
      background-color: #fff700;
      color: #000;
    }
    footer {
      background-color: #111;
      padding: 20px;
      text-align: center;
      font-size: 12px;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>🎮 EricPlay Games 🎮</h1>
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#juegos">Juegos</a>
      <a href="#sobre">Sobre Eric</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="inicio" style="padding: 40px; text-align: center;">
    <h2>¡Bienvenido a EricPlay Games!</h2>
    <p>Explora los mejores juegos desbloqueados. ¡Diversión asegurada! ⚽🎯🧠</p>
  </section>

  <section id="juegos" class="main">
    <div class="game"><h3>Euro Kick Tournament</h3><a href="https://ubg365.github.io/Euro-Kick-Tournament/" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>2048</h3><a href="https://ubg76.github.io/2048/" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Palabra del Día</h3><a href="https://wordle.danielfrg.com" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Tag</h3><a href="https://77pen.net/go/tag.html" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Recoil</h3><a href="https://77pen.net/go/recoil.html" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>A Small World Cup</h3><a href="https://77pen.net/go/a-small-world-cup.html" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Moto X3M</h3><a href="https://77pen.net/go/moto-x3m.html" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Geometry Dash</h3><a href="https://77pen.net/go/geometry-dash.html" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Penalty Kick Online</h3><a href="https://77pen.net/go/penalty-kick-online.html" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>That's Not My Neighbor</h3><a href="https://thatsnotmyneighbor.online/v11/" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Infinite Craft</h3><a href="https://infinitecraftrecipes.io/online" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Gun Mayhem 3</h3><a href="https://77pen.net/go/gun-mayhem-3.html" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Shell Shockers</h3><a href="https://orcatech2711.github.io/nano/games/shellshockers/index.html" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Bloxd.io</h3><a href="https://bloxd.io/" target="_blank"><button>¡Jugar!</button></a></div>
    <div class="game"><h3>Cat Mario</h3><a href="https://www.catmario.eu/" target="_blank"><button>¡Jugar!</button></a></div>
  </section>

  <section id="sobre" style="padding: 40px; text-align: center;">
    <h2>Sobre Eric</h2>
    <p>Me llamo Eric, tengo 11 años y soy un crack del fútbol. ¡El Dépor es el mejor equipo del mundo! ⚽💙</p>
  </section>

  <section id="contacto" style="padding: 40px; text-align: center;">
    <h2>Contacto</h2>
    <p>Puedes escribirme a: <strong>prado.ferreiro.eric@gmail.com</strong></p>
  </section>

  <footer>
    <p>© 2025 EricPlay Games. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
