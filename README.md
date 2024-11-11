<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú Restaurante de Mariscos</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
        }
        img {
            width: 200px;
            height: auto;
            margin-bottom: 20px;
        }
        .menu {
            display: flex;
            gap: 15px;
        }
        .menu a {
            text-decoration: none;
            padding: 10px 20px;
            background-color: #008080;
            color: #ffffff;
            border-radius: 5px;
            font-size: 16px;
            transition: background-color 0.3s;
        }
        .menu a:hover {
            background-color: #005f5f;
        }
    </style>
</head>
<body>

    <!-- Imagen centrada -->
    <img src="https://www.zarla.com/images/zarla-el-capitn-1x1-2400x2400-20210623-qwd94dfvgryrtdmx6r6r.png?crop=1:1,smart&width=250&dpr=2" alt="Logo del restaurante de mariscos">

    <!-- Menú de botones -->
    <div class="menu">
        <a href="clientes.php">Clientes</a>
        <a href="inventario.php">Inventario</a>
        <a href="pedido.php">Pedido</a>
        <a href="productos.php">Productos</a>
        <a href="provedores.php">Proveedores</a>
        <a href="login.html">login</a>
    </div>

</body>
</html>
