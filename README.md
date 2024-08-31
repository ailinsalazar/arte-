<html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página sistemas</title>
    <style>
        body {
            font-family: "Kristen ITC", sans-serif;
            text-align: center;
            background-color: #f3f3f3;
            color: purple;
            margin: 0;
            padding: 0;
        }

        .header {
            background-color: #e0bbff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }

        h1 {
            font-size: 50px;
            margin: 0;
        }

        h2 {
            font-family: "Century Gothic", sans-serif;
            color: black;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1><marquee behavior="alternate">ARTE</marquee></h1>
    </div>

    <div style="text-align: left;"> 
<img src="paleta.jpg" alt="Mi imagen alineada a la derecha" width=100 height>
</div>

    <p style="text-align: center; font-family: 'Century Gothic'; font-size: 16px; color: black;">
        El arte es una actividad humana que tiene como objetivo crear obras culturales. <br>
        Es una expresión de la creatividad humana que se manifiesta en obras que pueden ser apreciadas por los sentidos.<br>
        El arte puede ser una reproducción, construcción o expresión que deleita, <br>
        emociona o produce un choque.
    </p>

     <div style="text-align: right;"> 
<img src="arteee.jpg" alt="Mi imagen alineada a la derecha" width=100 height>
</div>

    <h2>Algunos tipos de arte son:</h2>

    <h3><a href="arte1.html" style="text-decoration: none; color: black;">Artes Estéticas o Espaciales</a></h3>
    <h3><a href="arte2.html" style="text-decoration: none; color: black;">Artes Mixtas</a></h3>
    <h3><a href="arte3.html" style="text-decoration: none; color: black;">Artes Escénicas</a></h3>

    <p style="text-align: left; font-family: 'Century Gothic'; font-size: 16px; color: blue;">
        Selecciona a qué artistas conoces:
    </p>

    <p style="text-align: left; font-family: 'Century Gothic'; font-size: 16px; color: black;">
        <input type="checkbox"> Pablo Picasso<br>
        <input type="checkbox"> Leonardo da Vinci<br>
        <input type="checkbox"> Vincent van Gogh<br>
        <input type="checkbox"> Diego Velázquez<br>
        <input type="checkbox"> Claude Monet<br>
    </p>

    <script type="text/javascript">
        var m1 = "¡HOLA!";
        var mensaje1 = m1.toUpperCase();
        alert(mensaje1);

        var m2 = "El arte es terapia...";
        var mensaje2 = m2.toUpperCase();
        alert(mensaje2);

        var nombre = prompt("Ingrese su nombre");
        document.write("Hola " + nombre + ", eso ha sido un poco sobre arte!");
        
        document.write("<br>" + new Date());
    </script>
</body>
</html>
