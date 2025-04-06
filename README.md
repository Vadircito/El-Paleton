
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Paletón</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/png" href="logo.png">
    <!-- Fuente Poppins desde Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap" rel="stylesheet">
</head>
<body>
    <header role="banner">
        <img src="logo.png" alt="Logo El Paletón" class="logo" role="img">
        <h1>El Paletón</h1>
        <p class="ubicacion" role="contentinfo">📍 Habana del Este, Alamar</p>
    </header>

    <section class="galeria">
        <h2>Paletas (100 CUP)</h2>
        <div class="productos">
            <div class="producto">
                <img src="paleta-chocolate.png" alt="Chocolate">
                <p>Chocolate 🍫</p>
            </div>
            <div class="producto">
                <img src="paleta-fresa.png" alt="Fresa">
                <p>Fresa 🍓</p>
            </div>
            <div class="producto">
                <img src="paleta-naranja.png" alt="Naranja Piña">
                <p>Naranja-Piña 🍊🍍</p>
            </div>
        </div>

        <h2>Vasos de helado (80 CUP)</h2>
        <div class="productos">
            <div class="producto">
                <img src="vaso-chocolate.png" alt="Chocolate Vaso">
                <p>Chocolate 🍫</p>
            </div>
            <div class="producto">
                <img src="vaso-fresa.png" alt="Fresa Vaso">
                <p>Fresa 🍓</p>
            </div>
            <div class="producto">
                <img src="vaso-naranja.png" alt="Naranja Piña Vaso">
                <p>Naranja-Piña 🍊🍍</p>
            </div>
        </div>
    </section>

    <section class="formulario-contacto">
        <h2>Haz tu pedido</h2>
        <form action="https://formspree.io/f/mwkgywzb" method="POST">
            <input type="text" name="nombre" placeholder="Tu nombre" required>
            <input type="tel" name="telefono" placeholder="Tu teléfono" required>
            <input type="text" name="sabor" placeholder="Sabor" required>
            <input type="number" name="cantidad" placeholder="Cantidad" min="1" required>
            <button type="submit" class="submit-button">Enviar pedido 🚀</button>
        </form>
    </section>

    <a href="https://wa.me/5353875602" class="whatsapp-button" target="_blank">💬 Escríbenos por WhatsApp</a>
    

    <footer>
        <p>© 2025 El Paletón 🍦</p>
    </footer>
</body>
</html>
