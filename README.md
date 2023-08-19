<!DOCTYPE html>
<html>
<head>
  <title>Granja de Pollos-Ecopluma</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #FFD700;
      color: #333;
      text-align: center;
      padding: 20px;
    }
    nav {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }
    .product-card {
      border: 1px solid #ddd;
      padding: 20px;
      margin: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .product-image {
      flex: 1;
      max-width: 40%;
    }
    .product-details {
      flex: 1;
      padding: 0 20px;
    }
    .product-details h3 {
      margin-top: 0;
    }
    .product-price {
      font-size: 24px;
      color: #FFD700;
      margin-bottom: 10px;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Granja de Pollos de Campo</h1>
    <p>Pollos saludables criados en entornos naturales.</p>
  </header>
  <nav>
    <a href="#">Inicio</a>
    <a href="#">Productos</a>
    <a href="#">Contacto</a>
  </nav>
  <div class="container">
    <div class="product-card">
      <div class="product-image">
        <img src="pollo1.jpg" alt="Pollo de Campo 1">
      </div>
      <div class="product-details">
        <h3>Pollo de Campo Gordo</h3>
        <p>Pollo criado en libertad, alimentado con granos naturales.</p>
        <p class="product-price">$15.99/kg</p>
        <button>Agregar al Carrito</button>
      </div>
    </div>
    <div class="product-card">
      <div class="product-image">
        <img src="pollo2.jpg" alt="Pollo de Campo 2">
      </div>
      <div class="product-details">
        <h3>Pollo de Campo pequeño
        </h3>
        <p>Pollo criado en entorno orgánico, sin químicos ni antibióticos.</p>
        <p class="product-price">$18.99/kg</p>
        <button>Agregar al Carrito</button>
      </div>
    </div>
    <!-- Agrega más productos aquí -->
  </div>
  <footer>
    <p>&copy; 2023 Granja de Pollos de Campo. Todos los derechos reservados.</p>
  </footer>
</body>
</html>

