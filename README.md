<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Te amo mi amocito</title>
  <style>
    body {
      background: linear-gradient(to bottom right, #ffe6ec, #ffd1dc);
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      padding: 40px;
    }

    h1 {
      color: #c2185b;
      font-size: 40px;
      margin-bottom: 30px;
    }

    .tarjeta {
      background: white;
      border-radius: 20px;
      padding: 30px;
      max-width: 500px;
      margin: 0 auto;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
    }

    .pastilla {
      width: 90%;
      background: linear-gradient(135deg, #ff4b7d, #ff8da1);
      border-radius: 20px;
      margin: 30px auto;
      color: white;
      font-weight: bold;
      font-size: 16px;
      padding: 20px;
      text-align: justify;
      display: none;
      box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
    }

    .corazon {
      font-size: 60px;
      color: #ff3366;
      margin-top: 30px;
      display: none;
    }

    .mensaje1,
    .mensaje2 {
      font-size: 20px;
      color: #880e4f;
      margin-top: 20px;
      display: none;
    }

    .boton {
      background: #ff4081;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 25px;
      font-size: 18px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .boton:hover {
      background: #e91e63;
    }

    audio {
      display: none;
      
    }
  </style>
</head>
<body>

  <h1>Te amo mi amocito</h1>

  <div class="tarjeta">
    <p>Presiona para ver cuánto te amo 💖</p>
    <button class="boton" onclick="mostrarPastilla()">Abrir</button>

    <div class="pastilla" id="pastilla">
      Mi amor: <br><br>
      Gracias por hacerme la persona más feliz que puede existir. Gracias por todo lo que me das día a día. Cada detalle tuyo es lo más hermoso de este mundo. <br><br>
      Gracias por dejarme ser parte de tu vida, por todos los momentos hermosos que hemos compartido, por cada sonrisa, cada abrazo y cada palabra llena de amor. <br><br>
      Por favor, nunca te vayas de mi lado. Yo sueño con que algún día seas la mamá de mis hijos, porque eres el único y verdadero amor que he tenido. Tienes todo lo que me hace feliz. <br><br>
      Esta carta me tomó días, pero cada palabra vale la pena, porque está escrita con el corazón. Gracias por existir, por ser tú, por amarme y por dejarme amarte. ❤️
    </div>

    <div class="mensaje1" id="mensaje1">Eres mi todo. Gracias por existir.</div>
    <div class="mensaje2" id="mensaje2">ATT: Tu amorcito, para la mujer más hermosa del mundo.</div>
    <div class="corazon" id="corazon">♥</div>
  </div>

  <audio id="musica" autoplay loop>
    <source src="https://youtu.be/2Vv-BfVoq4g?si=xCtFCgR_7JOmuRmZ" type="audio/mpeg">
    Tu navegador no soporta audio HTML5.
  </audio>

  <script>
    function mostrarPastilla() {
      document.getElementById('pastilla').style.display = 'block';
      document.getElementById('mensaje1').style.display = 'block';
      document.getElementById('mensaje2').style.display = 'block';
      document.getElementById('corazon').style.display = 'block';
      document.getElementById('musica').play();
    }
  </script>

</body>
</html>
