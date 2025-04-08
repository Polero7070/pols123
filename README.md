<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>POLS | REVOLUCIÓN</title>
    <link href="https://fonts.googleapis.com/css2?family=Archivo+Black&display=swap" rel="stylesheet">
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
      body {
        background-color: #fefefe;
        font-family: 'Archivo Black', sans-serif;
        color: #111;
        padding: 2rem;
        background-image: url('https://www.transparenttextures.com/patterns/pencil-dots.png');
      }
      header {
        text-align: center;
        margin-bottom: 3rem;
      }
      h1 {
        font-size: 3rem;
        letter-spacing: 2px;
        text-shadow: 1px 1px 0 #ccc;
      }
      .slogan {
        overflow: hidden;
        white-space: nowrap;
        border-right: 3px solid black;
        width: 24ch;
        animation: typing 4s steps(24), blink .75s step-end infinite;
        font-size: 1.5rem;
        margin: 1rem auto;
      }
      @keyframes typing {
        from { width: 0 }
        to { width: 24ch }
      }
      @keyframes blink {
        50% { border-color: transparent }
      }
      nav {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
        gap: 1rem;
        max-width: 800px;
        margin: 2rem auto;
      }
      nav a {
        display: block;
        padding: 1rem;
        background-color: #000;
        color: #fff;
        text-align: center;
        text-decoration: none;
        border-radius: 10px;
        box-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        transition: background-color 0.3s;
      }
      nav a:hover {
        background-color: #333;
      }
      footer {
        margin-top: 5rem;
        text-align: center;
        font-size: 0.9rem;
        color: #999;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>POLS / REVOLUCIÓN</h1>
      <div class="slogan">¿DÓNDE ESTÁ POLS?</div>
    </header>

    <nav>
      <a href="#">Remeras</a>
      <a href="#">Buzos</a>
      <a href="#">Jogging</a>
      <a href="#">Camisas</a>
      <a href="#">Camperas</a>
      <a href="#">Blazers</a>
      <a href="#">Guantes</a>
      <a href="#">Gorros</a>
    </nav>

    <footer>
      © POLS 2025 · REVOLUCIÓN es ahora.
    </footer>
  </body>
</html>
