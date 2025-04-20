<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ENSIGNA</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #222;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }

    .section {
      padding: 2rem;
    }

    h2 {
      margin-bottom: 1rem;
    }

    .card-container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1rem;
    }

    .card {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.2s ease-in-out;
    }

    .card:hover {
      transform: scale(1.03);
    }

    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .card-content {
      padding: 1rem;
    }

    .card-content h3 {
      margin: 0 0 0.5rem 0;
    }

    .card-content p {
      font-size: 0.9rem;
      color: #555;
    }
  </style>

</head>
<body>
  <header>
    <img src="https://i.pinimg.com/736x/3d/4c/6d/3d4c6dd3fb9490b4bd4be4e9420f8304.jpg" alt="Logo" width="350" height="350">
    <h2>Conectate al futuro, los mejores celulares al alcance de tu mano</h2>
  </header>

  <!-- Sección iPhone -->
  <section class="section">
    <h2>iPhone</h2>
    <div class="card-container">
      <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQtnog9bTejXB1QhypPtbQ0nvhIOpXdbcwyJw&s" alt="iPhone">
        <div class="card-content">
          <h3>iPhone 14 Pro blanco</h3>
          <p>7.225.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://co.tiendasishop.com/cdn/shop/files/IMG-12496118_d3a06b05-ba18-4aaf-a3ac-c1372d9d8490.jpg?v=1738685882" alt="iPhone">
        <div class="card-content">
          <h3>iPhone 13 128GB azul medianoche</h3>
          <p>2.800.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://assets.mmsrg.com/isr/166325/c1/-/ASSET_MP_95773265?x=536&y=402&format=jpg&quality=80&sp=yes&strip=yes&trim&ex=536&ey=402&align=center&resizesource&unsharp=1.5x1+0.7+0.02&cox=0&coy=0&cdx=536&cdy=402" alt="iPhone">
        <div class="card-content">
          <h3>iPhone 13 128GB rosado</h3>
          <p>2.800.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://m.media-amazon.com/images/I/51svQ-jqqQL.jpg" alt="iPhone">
        <div class="card-content">
          <h3>iPhone 12 64GB azul</h3>
          <p>2.000.000$</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Sección Xiaomi -->
  <section class="section">
    <h2>Xiaomi</h2>
    <div class="card-container">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_793915-MCO49579972961_042022-O.webp" alt="Xiaomi">
        <div class="card-content">
          <h3>Xiaomi Mi 11 Lite Dual Sim 128 Gb White 6 Gb Ram</h3>
          <p>2.000.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_602998-MCO51917968433_102022-O.webp" alt="Xiaomi">
        <div class="card-content">
          <h3>Xiaomi Redmi Note 11s 128 Gb 6 Gb Ram</h3>
          <p>1.300.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_704366-MCO54983276900_042023-O.webp" alt="Xiaomi">
        <div class="card-content">
          <h3>Xiaomi Poco X4 Pro 5g 2201116pg 8gb 256gb Dual Sim</h3>
          <p>1.600.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_917056-MLA82603183402_032025-O.webp" alt="Xiaomi">
        <div class="card-content">
          <h3>Celular Xiaomi Poco X7 5g 256gb 8gb Ram Green Color Verde Claro</h3>
          <p>1.100.000$</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Sección Oppo -->
  <section class="section">
    <h2>Oppo</h2>
    <div class="card-container">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_818505-MCO73549354791_122023-O.webp" alt="Oppo">
        <div class="card-content">
          <h3>Oppo Find X5 5g Cph2307 8gb 256gb Nano Sim + Esim</h3>
          <p>4.000.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="data:image/jpeg;base64,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" alt="Oppo">
        <div class="card-content">
          <h3>Oppo Reno12 F 5g Naranja</h3>
          <p>1.800.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_686833-MCO73456846132_122023-O.webp" alt="Oppo">
        <div class="card-content">
          <h3>Oppo A96 Cph2333 8gb 128gb Dual Sim Duos</h3>
          <p>2.700.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_935133-MCO53863701662_022023-O.webp" alt="Oppo">
        <div class="card-content">
          <h3>Oppo Find N2 Flip 5g Cph2437 8gb 256gb Dual Sim Duos</h3>
          <p>10.000.000</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Sección Motorola -->
  <section class="section">
    <h2>Motorola</h2>
    <div class="card-container">
      <div class="card">
        <img src="data:image/jpeg;base64,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" alt="Motorola">
        <div class="card-content">
          <h3>Moto G72 128 GB negro 6 GB RAM</h3>
          <p>900.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_694318-MCO77471826955_072024-O.webp" alt="Motorola">
        <div class="card-content">
          <h3>Motorola Edge 30 Ultra 256 Gb Negro Interstellar 12 Gb Ram</h3>
          <p>1.900.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_748029-MLU77505123257_072024-O.webp" alt="Motorola">
        <div class="card-content">
          <h3>Moto G60 Dual SIM 128 GB plata 4 GB RAM</h3>
          <p>600.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://comoto.vtexassets.com/arquivos/ids/165873-800-auto?v=638657407682130000&width=800&height=auto&aspect=true" alt="Motorola">
        <div class="card-content">
          <h3>motorola razr 50 Negro</h3>
          <p>4.000.000$</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Sección Samsung -->
  <section class="section">
    <h2>Samsung</h2>
    <div class="card-container">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_827439-MLU69141802500_042023-O.webp" alt="Samsung">
        <div class="card-content">
          <h3>Samsung Galaxy S23 Ultra (eSIM) 5G Dual SIM 256 GB phantom black 12 GB RAM</h3>
          <p>3.800.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_658679-MLA78222535177_082024-O.webp" alt="Samsung">
        <div class="card-content">
          <h3>Samsung Galaxy Z Fold6 Dual SIM 256 GB plateado 12 GB RAM</h3>
          <p>6.000.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_919569-CBT81977442480_022025-O.webp" alt="Samsung">
        <div class="card-content">
          <h3>Samsung Galaxy A54 5g + 4g Lte (128 Gb + 8 Gb)</h3>
          <p>3.000.000$</p>
        </div>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_751404-MLA50401798045_062022-O.webp" alt="Samsung">
        <div class="card-content">
          <h3>Samsung Galaxy A13 128 GB light blue 4 GB RAM</h3>
          <p>600.000$</p>
        </div>
      </div>
    </div>
  </section>

</body>
</html>
