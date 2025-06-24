<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Portafolio - Gonzalo Perez</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0f0f0f;
      color: #ffffff;
    }

    header {
      background-color: #1f1f1f;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #00ffcc;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    header p {
      color: #aaaaaa;
      margin: 5px 0 0;
    }

    .section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    .section h2 {
      color: #00ffcc;
      border-bottom: 1px solid #00ffcc;
      padding-bottom: 5px;
    }

    .project {
      margin-bottom: 20px;
    }

    .project-title {
      font-size: 1.3em;
      color: #ffffff;
    }

    .project-desc {
      color: #bbbbbb;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #1f1f1f;
      border-top: 1px solid #333;
      font-size: 0.9em;
      color: #777;
    }

    a {
      color: #00ffcc;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gonzalo</h1>
    <p>Programador en formación | Apasionado por la tecnología</p>
  </header>

  <section class="section">
    <h2>Sobre mí</h2>
    <p>
      Hola, soy un desarrollador principiante aprendiendo desarrollo web, móvil y bases de datos. Me interesa construir proyectos reales para mejorar mis habilidades y colaborar con otros programadores.
    </p>
  </section>

  <section class="section">
    <h2>Proyectos</h2>
    <div class="project">
      <div class="project-title">🧮 Organizador de Torneos (App móvil)</div>
      <div class="project-desc">App en Kotlin + Jetpack Compose + Firebase para gestionar torneos, equipos y resultados.</div>
    </div>
    <div class="project">
      <div class="project-title">📦 Control de Stock (Web)</div>
      <div class="project-desc">App fullstack en desarrollo junto a un amigo para gestionar productos y movimientos de inventario.</div>
    </div>
  </section>

  <section class="section">
    <h2>Contacto</h2>
    <p>📫 Puedes contactarme por GitHub: <a href="https://github.com/gnzperez" target="_blank">gnzperez</a></p>
    <p>✉️ Email: gonzalonperez98@gmail.com</p>
  </section>

  
</body>
</html>
