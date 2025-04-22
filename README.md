
    
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Página de Bioética</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #b3e5fc; /* azul celeste */
      color: white;
    }
    h1, h2, h3 {
      color: black;
    }
    header {
      background-color: #0288d1;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
    }
    header nav a:hover {
      text-decoration: underline;
    }
    .encuesta-btn {
      background-color: #ffeb3b;
      color: black;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .sidebar {
      width: 200px;
      position: fixed;
      top: 60px;
      left: 0;
      background-color: #0277bd;
      height: 100%;
      padding: 20px;
    }
    .sidebar a {
      display: block;
      color: white;
      padding: 10px 0;
      text-decoration: none;
    }
    .sidebar a:hover {
      background-color: #01579b;
    }
    .main {
      margin-left: 220px;
      padding: 20px;
    }
    .hero {
      background: url('hero-image.jpg') center/cover no-repeat;
      height: 400px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      text-align: center;
    }
    .hero h1 {
      font-size: 2em;
    }
    .hero button {
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #ff5722;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .section {
      margin: 40px 0;
    }
    .card-container {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }
    .card {
      background-color: #039be5;
      border-radius: 8px;
      padding: 15px;
      width: 200px;
      text-align: center;
    }
    footer {
      background-color: #01579b;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <div><strong>Logo Bioética</strong></div>
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#definicion">Definición</a>
      <a href="#historia">Histórico</a>
      <a href="#personajes">Personajes</a>
      <a href="#temas">Temas</a>
      <a href="#casos">Casos</a>
      <a href="#encuestas">Encuestas</a>
      <a href="#normatividad">Normatividad</a>
      <a href="#referencias">Referencias</a>
    </nav>
    <button class="encuesta-btn">Participa en Encuesta</button>
  </header>

  <div class="sidebar">
    <a href="#inicio">Inicio</a>
    <a href="#definicion">¿Qué es la Bioética?</a>
    <a href="#historia">Historia</a>
    <a href="#personajes">Personajes</a>
    <a href="#temas">Temas</a>
    <a href="#casos">Casos</a>
    <a href="#encuestas">Encuestas</a>
    <a href="#normatividad">Normatividad</a>
  </div>

  <div class="main">
    <section class="hero" id="inicio">
      <h1>Explora los dilemas éticos en la biomedicina y los avances científicos</h1>
      <button>Participa en Encuesta</button>
    </section>

    <section class="section" id="definicion">
      <h2>¿Qué es la Bioética?</h2>
      <p>La bioética estudia los dilemas morales que surgen en la biomedicina y las ciencias de la vida...</p>
    </section>

    <section class="section" id="historia">
      <h2>Historia de la Bioética</h2>
      <p>1971: Van Rensselaer Potter y la creación del término...</p>
    </section>

    <section class="section" id="personajes">
      <h2>Personajes Clave en la Bioética</h2>
      <div class="card-container">
        <div class="card"><strong>Van Rensselaer Potter</strong><br>"La bioética como puente entre biología y ética."</div>
        <div class="card"><strong>Peter Singer</strong><br>"Ética práctica para tiempos modernos."</div>
        <div class="card"><strong>Andrés Pacheco</strong><br>"Promoviendo los derechos humanos en la ciencia."</div>
      </div>
    </section>

    <section class="section" id="temas">
      <h2>Temas Principales</h2>
      <div class="card-container">
        <div class="card">Eutanasia</div>
        <div class="card">Aborto</div>
        <div class="card">Seguridad Alimentaria</div>
        <div class="card">Genética</div>
        <div class="card">Derechos Reproductivos</div>
        <div class="card">Sexualidad</div>
      </div>
    </section>

    <section class="section" id="casos">
      <h2>Casos Reales y Dilemas</h2>
      <div class="card-container">
        <div class="card">Terri Schiavo<br><button>Leer Más</button></div>
        <div class="card">Clonación de Dolly<br><button>Leer Más</button></div>
        <div class="card">Eutanasia en Colombia<br><button>Leer Más</button></div>
      </div>
    </section>

    <section class="section" id="encuestas">
      <h2>Tu Opinión es Importante</h2>
      <form>
        <label>¿Apoyas la eutanasia?<br><input type="radio" name="eutanasia" value="sí"> Sí <input type="radio" name="eutanasia" value="no"> No</label><br>
        <label>¿Debería regularse la ingeniería genética?<br><input type="radio" name="genetica" value="sí"> Sí <input type="radio" name="genetica" value="no"> No</label><br>
        <button type="submit">Enviar Encuesta</button>
      </form>
    </section>

    <section class="section" id="normatividad">
      <h2>Normativas y Legislación</h2>
      <ul>
        <li><a href="#" style="color: white;">Código Ético</a></li>
        <li><a href="#" style="color: white;">Ley sobre Eutanasia</a></li>
        <li><a href="#" style="color: white;">Convención sobre Biomedicina</a></li>
      </ul>
    </section>
  </div>

  <footer>
    <p>Contacto: bioetica@ejemplo.com | © Derechos de autor 2025</p>
    <p>Redes Sociales: @BioeticaEnLinea</p>
  </footer>
</body>
</html>
