<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bioética: Ciencia y Ética</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Bioética: Ciencia y Ética</h1>
    <nav>
      <ul>
        <li><a href="#definicion">¿Qué es la Bioética?</a></li>
        <li><a href="#historia">Historia</a></li>
        <li><a href="#temas">Temas Principales</a></li>
        <li><a href="#encuesta">Encuesta</a></li>
      </ul>
    </nav>
  </header>

  <section id="definicion">
    <h2>¿Qué es la Bioética?</h2>
    <p>La bioética es una disciplina que estudia los dilemas morales surgidos en la biomedicina y las ciencias de la vida.</p>
  </section>

  <section id="historia">
    <h2>Historia de la Bioética</h2>
    <p>La bioética moderna comenzó en la década de 1970, impulsada por el trabajo de Van Rensselaer Potter.</p>
  </section>

  <section id="temas">
    <h2>Temas Principales</h2>
    <ul>
      <li>Eutanasia</li>
      <li>Aborto</li>
      <li>Genética</li>
      <li>Derechos Reproductivos</li>
    </ul>
  </section>

  <section id="encuesta">
    <h2>Participa en la Encuesta</h2>
    <form>
      <label for="eutanasia">¿Apoyas la eutanasia?</label>
      <input type="radio" id="eutanasia" name="eutanasia" value="sí"> Sí
      <input type="radio" id="eutanasia" name="eutanasia" value="no"> No
      <br>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Bioética: Ciencia y Ética</p>
  </footer>
</body>
</html>
/* Estilos generales */
body {
  background-color: #87CEEB; /* Azul cielo */
  color: white;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #0000FF; /* Azul */
  padding: 10px;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 2em;
}

nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 20px;
}

section h2 {
  color: black;
}

footer {
  background-color: #0000FF; /* Azul */
  color: white;
  text-align: center;
  padding: 10px;
  position: fixed;
  width: 100%;
  bottom: 0;
}

 
