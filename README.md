<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi primer programa en HTML</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        section {
            padding: 20px;
        }
        button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenido a mi programa en HTML</h1>
    <p>Ejemplo sencillo con HTML, CSS y JavaScript</p>
</header>

<section>
    <h2>¿Qué hace este programa?</h2>
    <p>Al presionar el botón, aparecerá un mensaje en pantalla.</p>

    <button onclick="mostrarMensaje()">Haz clic aquí</button>

    <p id="mensaje"></p>
</section>

<footer>
    <p>Creado por el estudiante - 2025</p>
</footer>

<script>
    function mostrarMensaje() {
        document.getElementById("mensaje").innerHTML = "¡Hola! Este es tu primer programa en HTML 🎉";
    }
</script>

</body>
</html>
