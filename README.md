<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ball-Z Pizzería</title>
  <style>
    /* --- ESTILOS GENERALES --- */
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: linear-gradient(135deg, #ffb347, #ffcc33);
      color: #333;
    }

    header {
      background-color: #ff5733;
      color: white;
      text-align: center;
      padding: 25px;
      box-shadow: 0 3px 10px rgba(0, 0, 0, 0.3);
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      text-shadow: 2px 2px 5px #00000055;
    }

    nav {
      background-color: #ffa533;
      display: flex;
      justify-content: center;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      margin: 0 20px;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ff5733;
      background-color: white;
      padding: 5px 10px;
      border-radius: 8px;
    }

    .contenido {
      text-align: center;
      padding: 40px 20px;
    }

    .contenido h2 {
      color: #ff5733;
      font-size: 2em;
      margin-bottom: 15px;
    }

    .contenido p {
      font-size: 1.2em;
      max-width: 700px;
      margin: 0 auto 30px;
    }

    .menu {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 30px;
    }

    .pizza {
      background-color: white;
      border-radius: 15px;
      width: 250px;
      padding: 20px;
      box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s;
    }

    .pizza:hover {
      transform: scale(1.05);
    }

    .pizza img {
      width: 100%;
      border-radius: 15px;
    }

    .pizza h3 {
      color: #ff5733;
      margin: 10px 0 5px;
    }

    footer {
      background-color: #ff5733;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

    footer a {
      color: white;
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>🍕 Ball-Z Pizzería 🍕</h1>
    <p>¡Las delicias mas sabrosas ruedan!</p>
  </header>

  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#menu">Menú</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="inicio" class="contenido">
    <h2>Bienvenido a Ball-Z</h2>
    <p>Somos la pizzería más divertida y deliciosa de la ciudad. Nuestras pizzas son tan poderosas como una bola de energía... ¡Ball-Z te deja con hambre cero y poder máximo!</p>
    <img src="" alt="Texto alternativo">


  <section id="menu" class="contenido">
    <h2>Nuestro Menú</h2>
    <div class="menu">
      <div class="pizza">
        <img src="https://cdn.pixabay.com/photo/2020/12/16/03/32/pizza-5837331_1280.jpg" alt="Pizza Pepperoni">
        <h3>Pepperoni Z</h3>
        <p>Explosiva y llena de energía. Con extra de queso y pepperoni crujiente.</p>
      </div>
      <div class="pizza">
        <img src="https://cdn.pixabay.com/photo/2017/12/09/08/18/pizza-3007395_1280.jpg" alt="Pizza Vegetariana">
        <h3>Veggie Ball</h3>
        <p>Una combinación de vegetales que te hace sentir saludable y fuerte.</p>
      </div>
      <div class="pizza">
        <img src="https://cdn.pixabay.com/photo/2022/02/09/19/23/pizza-7003161_1280.jpg" alt="Pizza Cuatro Quesos">
        <h3>Queso Supremo</h3>
        <p>Cuatro tipos de queso fundidos en perfecta armonía. ¡Un poder legendario!</p>
      </div>
    </div>
  </section>

  <section id="contacto" class="contenido">
    <h2>Contáctanos</h2>
    <p>📍 Dirección: Calle 9 #123, Ciudad del Sabor</p>
    <p>📞 Teléfono: 310-555-BALL</p>
    <p>📧 Correo: <a href="mailto:ballzpizzeria@gmail.com">ballzpizzeria@gmail.com</a></p>
  </section>

  <footer>
    <p>© 2025 Ball-Z Pizzería | Diseñado por Juan Sanchez 🍕</p>
  </footer>
</body>
</html>
