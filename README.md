<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Paletón - Helados</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('https://source.unsplash.com/1600x900/?ice-cream'); /* Fondo de helados */
            background-size: cover;
            background-position: center;
            text-align: center;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        .container {
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
            width: 90%;
            max-width: 400px;
            margin: 50px auto;
        }
        img {
            width: 150px;
            border-radius: 10px;
        }
        h1 {
            font-size: 28px;
            margin: 10px 0;
        }
        .product {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(255, 255, 255, 0.2);
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
        }
        .product span {
            font-size: 18px;
        }
        .button {
            display: inline-block;
            background: #ffcc00;
            color: #000;
            padding: 10px 15px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="Paleton.png" alt="Logo El Paletón"> 
        <h1>El Paletón</h1>
        <p>📍 Habana del Este, Alamar</p>
        
        <h2>🍦 Paletas - 100 CUP</h2>
        <div class="product"><span>Chocolate</span></div>
        <div class="product"><span>Fresa</span></div>
        <div class="product"><span>Naranja Piña</span></div>

        <h2>🍨 Vasos de Helado - 80 CUP</h2>
        <div class="product"><span>Chocolate</span></div>
        <div class="product"><span>Fresa</span></div>
        <div class="product"><span>Naranja Piña</span></div>

        <a href="https://wa.me/53875602" class="button">📲 Pedir por WhatsApp</a>
    </div>

</body>
</html>
