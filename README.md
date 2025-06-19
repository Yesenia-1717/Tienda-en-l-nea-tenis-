# Tienda-en-l-nea-tenis-
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Productos - Mi tienda</title>
    <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
<header>
    <h1>Mi tienda</h1>
    <nav>
        <ul>
            <li><a href="index.html">Inicio</a></li>
            <li><a href="productos.html">Productos</a></li>
            <li><a href="carrito.html">Carrito</a></li>
            <li><a href="contacto.html">Contacto</a></li>
        </ul>
    </nav>
</header>

<main>
    <h2>Todos los productos</h2>
    <div class="productos">

        <div class="producto">
            <img src="imágenes/image1.jpg" width="250" alt="Tenis Total 90 Dorados">
            <h3>Total 90 Dorados</h3>
            <p><del>$8,000.00</del> $5,000.00</p>
            <button onclick="agregarAlCarrito('Total 90 Dorados', 5000)">Agregar al carrito</button>
        </div>

        <div class="producto">
            <img src="imágenes/image2.jpg" width="250" alt="Tenis Total 90 Rojos">
            <h3>Total 90 Rojos</h3>
            <p><del>$9,000.00</del> $6,000.00</p>
            <button onclick="agregarAlCarrito('Total 90 Rojos', 6000)">Agregar al carrito</button>
        </div>

        <div class="producto">
            <img src="imágenes/image3.jpg" width="250" alt="Zidane Retro">
            <h3>Zidane Retro</h3>
            <p><del>$13,000.00</del> $9,999.00</p>
            <button onclick="agregarAlCarrito('Zidane Retro', 9999)">Agregar al carrito</button>
        </div>

        <div class="producto">
            <img src="imágenes/image4.jpg" width="250" alt="Zidane Dorados">
            <h3>Zidane Dorados</h3>
            <p><del>$15,000.00</del> $12,999.00</p>
            <button onclick="agregarAlCarrito('Zidane Dorados', 12999)">Agregar al carrito</button>
        </div>

        <div class="producto">
            <img src="imágenes/image5.jpg" width="250" alt="Adidas Predator Absolute Gold Edición Especial Zinedine">
            <h3>Adidas Predator Absolute Gold Edición Especial Zinedine</h3>
            <p><del>$7,000.00</del> $4,000.00</p>
            <button onclick="agregarAlCarrito('Adidas Predator Absolute Gold Edición Especial Zinedine', 4000)">Agregar al carrito</button>
        </div>
    </div>
</main>

<script src="js/carrito.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inicio - Mi tienda</title>
    <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
<header>
    <h1>Mi tienda</h1>
    <nav>
        <ul>
            <li><a href="index.html">Inicio</a></li>
            <li><a href="productos.html">Productos</a></li>
            <li><a href="carrito.html">Carrito</a></li>
            <li><a href="contacto.html">Contacto</a></li>
        </ul>
    </nav>
</header>

<main>
    <h2>Ofertas del día</h2>
    <div class="productos">
        <div class="producto">
            <img src="imágenes/image1.jpg" width="250" alt="Tenis Nike Rojos">
            <h3>Tenis Nike Rojos</h3>
            <p><del>$14,000.00</del> $9,000.00</p>
            <button onclick="agregarAlCarrito('Tenis Nike Rojos', 9000)">Agregar al carrito</button>
        </div>
        <div class="producto">
            <img src="imágenes/image2.jpg" width="250" alt="Zidane Retro">
            <h3>Zidane Retro</h3>
            <p><del>$13,000.00</del> $9,999.00</p>
            <button onclick="agregarAlCarrito('Zidane Retro', 9999)">Agregar al carrito</button>
        </div>
    </div>
</main>

<script src="js/carrito.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carrito</title>
    <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
<header>
    <h1>Tu carrito</h1>
    <nav>
        <ul>
            <li><a href="index.html">Inicio</a></li>
            <li><a href="productos.html">Productos</a></li>
            <li><a href="carrito.html">Carrito</a></li>
            <li><a href="contacto.html">Contacto</a></li>
        </ul>
    </nav>
</header>

<main>
    <ul id="lista-carrito"></ul>
    <p id="total-carrito">Total: $0.00</p>
</main>

<script src="js/carrito.js"></script>
</body>
</html>

 <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contacto - Mi tienda</title>
  <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
  <header>
    <h1>Mi tienda</h1>
    <nav>
      <ul>
        <li><a href="index.html">Inicio</a></li>
        <li><a href="productos.html">Productos</a></li>
        <li><a href="carrito.html">Carrito</a></li>
        <li><a href="contacto.html">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>Contáctanos</h2>
    <form>
      <label for="nombre">Nombre:</label><br />
      <input type="text" id="nombre" name="nombre" required><br><br>

      <label for="email">Correo electrónico:</label><br />
      <input type="email" id="email" name="email" required><br><br>

      <label for="mensaje">Mensaje:</label><br />
      <textarea id="mensaje" name="mensaje" rows="5" required></textarea><br><br>

      <button type="submit">Enviar</button>
    </form>
  </main>

  <script src="js/funciones.js"></script>
</body>
</html>

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: lightgreen;
    margin: 0;
    padding: 0;
}

header {
    background-color: green;
    color: #fff;
    padding: ;
    text-align: justify;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

.productos {
    display: flex;
    gap: 1em;
    flex-wrap: wrap;
    padding: 1em;
}

.producto {
    background-color: white;
    padding: 1em;
    border: 1px solid #ccc;
    width: 250px;

    
    text-align: center;
}

https://github.com/Yesenia-1717/Tienda-en-l-nea-tenis-/blob/main/image1.jpg
https://github.com/Yesenia-1717/Tienda-en-l-nea-tenis-/blob/main/image2.jpg
https://github.com/Yesenia-1717/Tienda-en-l-nea-tenis-/blob/main/image3.jpg




