
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vinilos y CDs Online</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Tienda de Vinilos y CDs</h1>
        <nav>
            <ul>
                <li><a href="#home">Inicio</a></li>
                <li><a href="#vinilos">Vinilos</a></li>
                <li><a href="#cds">CDs</a></li>
                <li><a href="#carrito">Carrito</a></li>
            </ul>
        </nav>
    </header>

    <section id="vinilos">
        <h2>Vinilos</h2>
        <div class="productos">
            <div class="producto">
                <img src="vinilo1.jpg" alt="Vinilo 1">
                <h3>Álbum 1 - Artista 1</h3>
                <p>$20.00</p>
                <button onclick="agregarAlCarrito('Álbum 1', 20)">Añadir al carrito</button>
            </div>
            <div class="producto">
                <img src="vinilo2.jpg" alt="Vinilo 2">
                <h3>Álbum 2 - Artista 2</h3>
                <p>$25.00</p>
                <button onclick="agregarAlCarrito('Álbum 2', 25)">Añadir al carrito</button>
            </div>
            <!-- Añade más productos según sea necesario -->
        </div>
    </section>

    <section id="cds">
        <h2>CDs</h2>
        <div class="productos">
            <div class="producto">
                <img src="cd1.jpg" alt="CD 1">
                <h3>Álbum 1 - Artista 1</h3>
                <p>$10.00</p>
                <button onclick="agregarAlCarrito('Álbum CD 1', 10)">Añadir al carrito</button>
            </div>
            <div class="producto">
                <img src="cd2.jpg" alt="CD 2">
                <h3>Álbum 2 - Artista 2</h3>
                <p>$12.00</p>
                <button onclick="agregarAlCarrito('Álbum CD 2', 12)">Añadir al carrito</button>
            </div>
            <!-- Añade más productos según sea necesario -->
        </div>
    </section>

    <section id="carrito">
        <h2>Carrito de Compras</h2>
        <div id="listaCarrito">
            <p>Tu carrito está vacío.</p>
        </div>
        <p>Total: $<span id="totalCarrito">0.00</span></p>
        <button onclick="procesarPago()">Pagar</button>
    </section>

    <script src="script.js"></script>
</body>
</html>
