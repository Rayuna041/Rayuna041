<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Zapatos y Gorras</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Tienda de Zapatos y Gorras</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <h2>Bienvenidos a nuestra tienda</h2>
        <p>Encuentra los mejores zapatos y gorras aquí.</p>
    </section>

    <section id="productos">
        <h2>Productos</h2>
        <div class="producto">
            <img src="zapato1.jpg" alt="Zapato 1">
            <h3>Zapato Deportivo</h3>
            <p>$50.00</p>
        </div>
        <div class="producto">
            <img src="gorra1.jpg" alt="Gorra 1">
            <h3>Gorra Casual</h3>
            <p>$20.00</p>
        </div>
    </section>

    <section id="sobre-nosotros">
        <h2>Sobre Nosotros</h2>
        <p>Somos una tienda dedicada a ofrecer los mejores zapatos y gorras del mercado.</p>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <form action="enviar_mensaje.php" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Tienda de Zapatos y Gorras. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

