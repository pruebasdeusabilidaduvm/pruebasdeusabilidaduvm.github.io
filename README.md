<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pruebas de Usabilidad - UVM</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #000;
        }
        header {
            background-color: #f00;
            padding: 20px;
            text-align: center;
            color: #fff;
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        .image-text {
            margin-top: 20px;
            text-align: center;
        }
        .video-container {
            position: relative;
            padding-bottom: 56.25%;
            padding-top: 30px;
            height: 0;
            overflow: hidden;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        .button {
            display: inline-block;
            background-color: #000;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }
        footer {
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .footer-button {
            display: inline-block;
            background-color: #fff;
            color: #000;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin: 0 10px;
        }
        .resource {
            margin-top: 50px;
            text-align: left;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        .resource h2 {
            color: #f00;
            width: 100%;
            text-align: center;
        }
        .resource p {
            margin-bottom: 10px;
        }
        .resource-article {
            width: calc(33.33% - 20px); /* 3 articles with margin-right */
            margin-bottom: 20px;
            text-align: center;
        }
        .resource-article img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
        }
        .resource-button {
            background-color: #000;
            color: #fff;
            padding: 5px 10px;
            text-decoration: none;
            border-radius: 3px;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://1000marcas.net/wp-content/uploads/2020/03/Logo.-Universidad-Del-Valle-de-Mexicopng.png" alt="Logo UVM" width="150">
        <h1>Pruebas de Usabilidad</h1>
    </header>
    <div class="content">
        <div class="resource">
            <h2>Recursos</h2>
            <div class="resource-article">
                <img src="https://aunmasdificiltodavia.es/wp-content/uploads/2023/11/usabilidad-navegabilidad-web-puntos-a-tener-en-cuenta.jpg" alt="Principios de usabilidad web" width="150">
                <p>Los principios de usabilidad web de Jakob Nielsen son la base de cualquier página web para que sea “user friendly”.</p>
                <a href="https://es.semrush.com/blog/usabilidad-web-principios-jakob-nielsen/" class="resource-button" target="_blank">Leer más</a>
            </div>
            <div class="resource-article">
                <img src="https://baetica.com/wp-content/uploads/2020/09/experiencia-usuario-featured-baetica-780x780.jpg" alt="La usabilidad web y su impacto" width="150">
                <p>Descubre la importancia de la usabilidad web, los factores que la determinan y su influencia en la experiencia de usuario.</p>
                <a href="https://global.tiffin.edu/noticias/usabilidad-web-y-su-impacto-en-la-experiencia-del-usuario" class="resource-button" target="_blank">Leer más</a>
            </div>
            <div class="resource-article">
                <img src="https://efyntunuxaw.exactdn.com/wp-content/uploads/2019/02/Claves-para-crear-una-experiencia-de-usuario-excelente.jpg?strip=all&lossy=1&ssl=1" alt="Posicionamiento y otras ventajas de la usabilidad web" width="150">
                <p>Mejorando la experiencia del usuario para el posicionamiento.</p>
                <a href="https://dossetenta.com/mejorando-la-experiencia-del-usuario-la-importancia-de-la-usabilidad-web/" class="resource-button" target="_blank">Leer más</a>
            </div>
        </div>
        <div class="image-text">
            <img src="https://img.freepik.com/foto-gratis/elegante-mujer-sonriente-gafas-camisa-rayas-usando-computadora-portatil-mientras-sienta-mesa-cocina_171337-13030.jpg" alt="Chica en computadora" width="400">
            <p><strong>¿Qué es la usabilidad?</strong><br>
            La usabilidad web se refiere a la medida en que un sitio web puede ser utilizado de manera efectiva, eficiente y satisfactoria por sus usuarios. Implica la facilidad con la que los usuarios pueden navegar por el sitio, encontrar lo que están buscando y completar las tareas deseadas. La usabilidad web se basa en principios de diseño centrados en el usuario, que incluyen la claridad, la consistencia, la accesibilidad y la capacidad de respuesta del sitio.</p>
        </div>
        <div class="image-text">
            <img src="https://www.digitalmenta.com/wp-content/uploads/2019/05/usabilidad-web-1-min.jpg" alt="Chicos estudiando con computadoras" width="400">
            <p><strong>La importancia de la usabilidad web</strong><br>
            La importancia de la usabilidad web radica en su capacidad para mejorar la experiencia del usuario. Cuando un sitio web es fácil de navegar, presenta información de manera clara y permite a los usuarios cumplir sus objetivos de manera eficiente, se genera una experiencia positiva que puede generar lealtad hacia la marca y aumentar las probabilidades de que los usuarios regresen en el futuro.</p>
        </div>
        <div class="video-container">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/k6t0YxHG8IY" frameborder="0" allowfullscreen></iframe>
        </div>
        <a href="https://blog.hubspot.es/website/pruebas-usabilidad" target="_blank" class="button">QUIERO CONOCER MÁS</a>
        <div class="location">
            <h2>CONOCE NUESTRA UBICACIÓN</h2>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3761.365067453125!2d-99.22274188510522!3d19.368091786927282!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85d1ff097e19b931%3A0x84f7b386bc5e0983!2sUniversidad%20del%20Valle%20de%20M%C3%A9xico%20(Plantel%20Tlalpan)!5e0!3m2!1ses!2smx!4v1646062136147!5m2!1ses!2smx" width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
    </div>
    <footer>
        <a href="https://www.facebook.com/" target="_blank" class="footer-button">Facebook</a>
        <a href="https://www.whatsapp.com/?lang=es_LA" target="_blank" class="footer-button">WhatsApp</a>
        <a href="https://www.google.com/intl/es-419/gmail/about/" target="_blank" class="footer-button">Email</a>
        <p>© 2024 Universidad del Valle de México. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
