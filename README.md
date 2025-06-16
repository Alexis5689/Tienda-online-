# Tienda-online-
<!DOCTYPE html>

<html lang="es">
<head>
  <meta chartset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-escale=1.0"
  <title>Mi tienda en linea</title>
    <link rel="stylesheet" href="CSS/estilos.css">
    <link rel="stylesheet" href="CSS/responsive.css">
</head>
<body>
  <header>
    <h1>Mi tienda</h1>
    <nav>
      <ul>
        <li><a href="index.html">Inicio</a></li>
        <li><a href="productos .html">Productos</a></li>
        <li><a href="contacto.html">Contacto</a></li>
        <li><a href="carrito.html">Carrito</a></li>
        </ul>
    </nav>
    <section class="busqueda">
      <input type="text" id="buscador"
        placeholder="buscar productos.."
        oninput="filtrarproductos()"/>
    </section>
 </header>
  <main>
    <h2>Bienvebido a nuestra tienda en linea</h2>
    <p>Encuentra los mejores productos al mejor precio.</p>
    <section class="ofertas">
      <h2>Ofertas del dia</h2>
      <div class="productos">
        <img src="umagenes/ce10.webp" alt="Laptop Gamer"/>
        <figcaption>
          <h3>Readmi Note 14 Pro</h3>
          <p class="descripcion">Memoria RAM 8 GB -Procesador Mediatek</p>
          <p class="precio-oferta"><del>$15,000.00</del>$12,999.00</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="agregarALCarrito('Laptop Gamer',12999)">
            Agregar al carriti</button>
        </figcaption>
      </div>
    </section>
  <h1>
  </h1>
</body>
  <div class="productos">
        <img src="umagenes/ce10.webp" alt="Laptop Gamer"/>
          <figcaption>
          <h3>Oppo reno 12</h3>
          <p class="descripcion">Memoria RAM 8 GB -Procesador Mediatek</p>
          <p class="precio-oferta"><del>$20,000.00</del>$16,999.00</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="agregarALCarrito('Laptop Gamer',12999)">
            Agregar al carriti</button>
          </div>
        </figcaption>
   <figcaption>
     <div class="productos">
        <img src="umagenes/ce10.webp" alt="Laptop Gamer"/>
          <h3>HONOR x8b</h3>
          <p class="descripcion">Memoria RAM 8 GB -Procesador Mediatek</p>
          <p class="precio-oferta"><del>$18,000.00</del>$15,999.00</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="agregarALCarrito('Laptop Gamer',12999)">
            Agregar al carriti</button>
        </figcaption>
     </div>
     <figcaption>
       <div class="productos">
        <img src="umagenes/ce10.webp" alt="Laptop Gamer"/>
          <h3>0ppo reno 10</h3>
          <p class="descripcion">Memoria RAM 7 GB -Procesador Mediatek</p>
          <p class="precio-oferta"><del>$15,000.00</del>$9,999.00</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="agregarALCarrito('Laptop Gamer',12999)">
            Agregar al carriti</button>
        </figcaption>
       </div>
       <div class="productos">
        <img src="umagenes/ce10.webp" alt="Laptop Gamer"/>
  <h3>Galaxi s24 Ultra </h3>
          <p class="descripcion">Memoria RAM 10 GB -Procesador Mediatek</p>
          <p class="precio-oferta"><del>$19,000.00</del>$17,999.00</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="agregarALCarrito('Laptop Gamer',12999)">
            Agregar al carriti</button>
        </figcaption>
  </div>
       <div class="productos">
        <img src="umagenes/ce10.webp" alt="Laptop Gamer"/>
 <h3>HUAWEI Nova 11 </h3>
          <p class="descripcion">Memoria RAM 7 GB -Procesador Mediatek</p>
          <p class="precio-oferta"><de>$10,000.00</del>$8,999.00</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="agregarALCarrito('Laptop Gamer',12999)">
            Agregar al carriti</button>
        </figcaption>
  </div>
</figcaption>
     <div class="productos">
        <img src="umagenes/ce10.webp" alt="Laptop Gamer"/>
 <h3>HUAWEI FreeClip </h3>
          <p class="descripcion">Control de gestos, Audio especial HD</p>
          <p class="precio-oferta"><del>$16,000.00</del>$6,999.00</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="agregarALCarrito('Laptop Gamer',12999)">
            Agregar al carriti</button>
       
        </figcaption>

</div>
</html>
