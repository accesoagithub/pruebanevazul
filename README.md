# pruebanevazul
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Nevazul - Página oficial con productos y servicios de alta calidad">
    <title>Nevazul</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <script defer src="scripts.js"></script>
</head>
<body>
    <header>
        <div class="container">
            <h1>Nevazul</h1>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#nosotros">Nosotros</a></li>
                    <li><a href="#productos">Productos</a></li>
                    <li><a href="#blog">Blog</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <main>
        <section id="inicio">
            <div class="container">
                <h2>Bienvenidos a Nevazul</h2>
                <p>Ofrecemos productos y servicios de alta calidad para satisfacer sus necesidades.</p>
            </div>
        </section>
        
        <section id="nosotros">
            <div class="container">
                <h2>Sobre Nosotros</h2>
                <p>En Nevazul, nos comprometemos a ofrecer lo mejor en calidad y servicio.</p>
            </div>
        </section>
        
        <section id="productos">
            <div class="container">
                <h2>Nuestros Productos</h2>
                <div class="product-list">
                    <div class="product-item">
                        <img src="images/product1.jpg" alt="Producto 1">
                        <h3>Producto 1</h3>
                        <p>Descripción del producto 1.</p>
                    </div>
                    <div class="product-item">
                        <img src="images/product2.jpg" alt="Producto 2">
                        <h3>Producto 2</h3>
                        <p>Descripción del producto 2.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="blog">
            <div class="container">
                <h2>Blog</h2>
                <article>
                    <h3>Título del Artículo</h3>
                    <p>Contenido del artículo del blog.</p>
                </article>
            </div>
        </section>
        
        <section id="contacto">
            <div class="container">
                <h2>Contacto</h2>
                <form action="contacto.php" method="post">
                    <label for="nombre">Nombre:</label>
                    <input type="text" id="nombre" name="nombre" required>
                    
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                    
                    <label for="mensaje">Mensaje:</label>
                    <textarea id="mensaje" name="mensaje" required></textarea>
                    
                    <button type="submit">Enviar</button>
                </form>
            </div>
        </section>
    </main>
    
    <footer>
        <div class="container">
            <p>&copy; 2024 Nevazul. Todos los derechos reservados.</p>
        </div>
    </footer>
</body>
</html>
