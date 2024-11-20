<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Digital Products Store</title>
    <style>
        /* Global styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7fc;
            color: #333;
        }

        h1, h2, h3 {
            margin: 0;
            color: #333;
        }

        /* Header */
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.1em;
        }

        /* Main content section */
        .main-content {
            padding: 40px 20px;
            text-align: center;
        }

        .main-content h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .product-card {
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s ease;
        }

        .product-card:hover {
            transform: translateY(-10px);
        }

        .product-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .product-card .card-content {
            padding: 15px;
        }

        .product-card h3 {
            font-size: 1.5em;
            margin: 10px 0;
        }

        .product-card p {
            font-size: 1.1em;
            color: #777;
            margin-bottom: 15px;
        }

        .product-card .price {
            font-size: 1.4em;
            color: #27ae60;
            font-weight: bold;
            margin-bottom: 15px;
        }

        .product-card .buy-btn {
            background-color: #27ae60;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .product-card .buy-btn:hover {
            background-color: #2ecc71;
        }

        /* Footer */
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }

        footer p {
            font-size: 1em;
        }

        .cta-section {
            background-color: #2980b9;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        .cta-section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .cta-section p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }

        .cta-section .cta-btn {
            background-color: #e74c3c;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .cta-section .cta-btn:hover {
            background-color: #c0392b;
        }
    </style>
</head>
<body>
    <header>
        <h1>Premium Digital Products</h1>
        <p>Unlock Your Potential with Top-Quality Digital Downloads</p>
    </header>

    <div class="main-content">
        <h2>Our Best-Selling Products</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="https://via.placeholder.com/300x200" alt="Product 1">
                <div class="card-content">
                    <h3>Digital Product 1</h3>
                    <p>Transform your productivity with this powerful tool.</p>
                    <div class="price">$29.99</div>
                    <a href="#" class="buy-btn">Buy Now</a>
                </div>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/300x200" alt="Product 2">
                <div class="card-content">
                    <h3>Digital Product 2</h3>
                    <p>Take your skills to the next level with this amazing guide.</p>
                    <div class="price">$19.99</div>
                    <a href="#" class="buy-btn">Buy Now</a>
                </div>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/300x200" alt="Product 3">
                <div class="card-content">
                    <h3>Digital Product 3</h3>
                    <p>Boost your creativity with our cutting-edge digital design pack.</p>
                    <div class="price">$49.99</div>
                    <a href="#" class="buy-btn">Buy Now</a>
                </div>
            </div>
        </div>
    </div>

    <div class="cta-section">
        <h2>Get Started Today!</h2>
        <p>Ready to boost your productivity? Shop now and experience the difference!</p>
        <a href="#" class="cta-btn">Shop Now</a>
    </div>

    <footer>
        <p>&copy; 2024 Premium Digital Products. All rights reserved.</p>
    </footer>
</body>
</html>