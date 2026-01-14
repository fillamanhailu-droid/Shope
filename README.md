<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Shop</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f4f4f4;
        }
        header {
            background: #111;
            color: #fff;
            padding: 15px;
            text-align: center;
        }
        .container {
            padding: 15px;
        }
        .product {
            background: #fff;
            padding: 15px;
            margin-bottom: 15px;
            border-radius: 8px;
        }
        .product img {
            width: 100%;
            border-radius: 8px;
        }
        .price {
            color: green;
            font-size: 18px;
            font-weight: bold;
        }
        button {
            background: #25d366;
            color: white;
            border: none;
            padding: 10px;
            width: 100%;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #ddd;
            font-size: 14px;
        }
    </style>
</head>
<body>

<header>
    <h1>My Online Shop</h1>
    <p>Order easily via WhatsApp</p>
</header>

<div class="container">

    <div class="product">
        <img src="https://via.placeholder.com/400x250" alt="Product">
        <h2>Shega Burger</h2>
        <p>Delicious fresh burger</p>
        <p class="price">300 ETB</p>
        <button onclick="order()">Order Now</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/400x250" alt="Product">
        <h2>Pizza</h2>
        <p>Hot & tasty pizza</p>
        <p class="price">450 ETB</p>
        <button onclick="order()">Order Now</button>
    </div>

</div>

<footer>
    © 2026 My Shop | Delivery Available
</footer>

<script>
    function order() {
        window.location.href =
        "https://wa.me/251993076201?text=Hello%20I%20want%20to%20order";
    }
</script>

</body>
</html>
