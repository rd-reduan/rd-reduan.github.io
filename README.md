<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RS e-commerce</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 10px;
        }
        nav ul li {
            margin: 0 20px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2rem;
        }
        .container {
            width: 80%;
            margin: 20px auto;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        .product-card {
            background-color: #fff;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s ease;
        }
        .product-card:hover {
            transform: translateY(-5px);
        }
        .product-card img {
            max-width: 100%;
            height: 200px;
            object-fit: contain;
        }
        .product-card h3 {
            margin: 15px 0;
        }
        .product-card p {
            color: #555;
        }
        .product-card .price {
            font-size: 1.5rem;
            color: #e67e22;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>RS E-COMMERCE</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="https://www.facebook.com/profile.php?id=100083370991580">Contact Us</a></li>
                <li><a href="https://wa.me/qr/P4KPGGP4JT6VP1">WhatsApp</a></li>
            </ul>
        </nav>
    </header>
    <!-- CSS for Button Styling -->
<style>
    .buy-now-btn {
        text-decoration: none;
    }

    .buy-now-btn button {
        background-color: #28a745; /* Green background */
        color: white; /* White text */
        border: none; /* Remove default border */
        padding: 10px 20px; /* Padding inside the button */
        font-size: 16px; /* Font size */
        cursor: pointer; /* Change cursor to pointer on hover */
        border-radius: 5px; /* Rounded corners */
        box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1); /* Subtle shadow */
        transition: background-color 0.3s ease; /* Smooth color transition */
    }

    .buy-now-btn button:hover {
        background-color: #218838; /* Darker green on hover */
    }
</style>

    <div class="container">
        <h2>Our Products</h2>
        <div class="products">
            <!-- Product 1 -->
            <div class="product-card">
                <img src="https://i.ibb.co.com/fx3Kgp4/480ef5206609531-66cf45e7281a8.jpg" alt="Jersey-1">
                <h3>Jersey-1</h3>
                <p>Comfortable and stylish Jersey</p>
                <p class="price">Contact For Price</p>
                  <!-- Buy Now Button -->
            <a href="https://www.facebook.com/profile.php?id=100083370991580" class="buy-now-btn">
                <button>Buy Now</button>
            </a>
            </div>

            <!-- Product 2 -->
            <div class="product-card">
                <img src="https://i.ibb.co.com/pPkr10c/a27fbf202170471-6681b8f92aad5.jpg" alt="Jersey-2">
                <h3>Jersey-2</h3>
                <p>High-quality sports jersey</p>
                <p class="price">Contact For Price</p>
                <!-- Buy Now Button -->
            <a href="https://www.facebook.com/profile.php?id=100083370991580" class="buy-now-btn">
                <button>Buy Now</button>
            </a>
            </div>

            <!-- Product 3 -->
            <div class="product-card">
                <img src="https://i.ibb.co.com/L81MJp3/d2b089206230859-66c8a5e20e089.jpg" alt="Jersey-3">
                <h3>Jersey-3</h3>
                <p>Stylish Jersey.</p>
                <p class="price">Contact For Price</p>
                <!-- Buy Now Button -->
            <a href="https://www.facebook.com/profile.php?id=100083370991580" class="buy-now-btn">
                <button>Buy Now</button>
            </a>
            </div>

            <!-- Add more products as needed -->
        </div>
    </div>

    <footer>
        <p>&copy; 2024 RS e-commerce. All rights reserved.</p>
    </footer>
</body>
</html>
