<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Información del Perro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            text-align: center; /* Centra el contenido del contenedor */
        }
        h1 {
            text-align: center;
        }
        .info {
            margin-bottom: 10px;
        }
        .info label {
            font-weight: bold;
        }
        /* Estilo para la imagen */
        img {
            max-width: 100%; /* Ajusta el ancho máximo de la imagen al tamaño del contenedor */
            height: auto; /* Ajusta automáticamente la altura de la imagen para mantener la proporción */
            margin-bottom: 20px; /* Espacio inferior para separar la imagen del resto del contenido */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Información del Perro</h1>
        <!-- Cambia la ruta de la imagen por la que deseas mostrar -->
        <img src="C:\Users\snmin\Documents\Perros\WhatsApp Image 2024-04-12 at 2.23.11 PM.jpeg.jpeg" alt="Imagen del Perro" style="width: 300px;"> <!-- Cambia el valor de "width" según el tamaño deseado -->
        <div class="info">
            <label for="nombre">Nombre del Perro:</label>
            <span id="nombre">Ruffo</span>
        </div>
        <div class="info">
            <label for="raza">Raza:</label>
            <span id="raza">Pincher</span>
        </div>
        <div class="info">
            <label for="ano">Año:</label>
            <span id="ano">7 años</span>
        </div>
        <div class="info">
            <label for="telefono">Número de Celular:</label>
            <span id="telefono">3166324900</span>
        </div>
        <div class="info">
            <label for="direccion">Dirección:</label>
            <span id="direccion">Calle 73a #3-04 Tercer Milenio</span>
        </div>
    </div>
</body>
</html>
