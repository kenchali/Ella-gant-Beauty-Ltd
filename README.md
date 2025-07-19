<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ella'gant Beauty - Premium Beauty Products</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #d4a5a5;
            padding: 20px;
            text-align: center;
            color: white;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            background-color: #e8c3c3;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        nav a:hover {
            color: #d4a5a5;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1200x400?text=Welcome+to+Ella%27gant+Beauty');
            background-size: cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .hero h2 {
            font-size: 2em;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 10px 20px;
            border-radius: 5px;
        }
        .products {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .products h2 {
            text-align: center;
            margin-bottom: 30px;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 15px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .product h3 {
            margin: 10px 0;
            font-size: 1.2em;
        }
        .product p {
            margin: 5px 0;
            font-size: 1em;
            color: #666;
        }
        .product button {
            background-color: #d4a5a5;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }
        .product button:hover {
            background-color: #b88a8a;
        }
        footer {
            background-color: #d4a5a5;
            padding: 20px;
            text-align: center;
            color: white;
            margin-top: 40px;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ella'gant Beauty</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="home" class="hero">
        <h2>Welcome to Ella'gant Beauty – Where Elegance Meets Radiance</h2>
    </section>
    <section id="products" class="products">
        <h2>Our Premium Beauty Products</h2>
        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/250x250?text=Moisturizer" alt="Hydrating Moisturizer">
                <h3>Hydrating Moisturizer</h3>
                <p>$29.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250x250?text=Lipstick" alt="Matte Lipstick">
                <h3>Matte Lipstick</h3>
                <p>$19.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250x250?text=Foundation" alt="Liquid Foundation">
                <h3>Liquid Foundation</h3>
                <p>$34.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250x250?text=Mascara" alt="Volumizing Mascara">
                <h3>Volumizing Mascara</h3>
                <p>$24.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>
    <section id="about" class="products">
        <h2>About Us</h2>
        <p>Ella'gant Beauty is dedicated to providing high-quality beauty products that enhance your natural elegance. Our curated selection ensures premium ingredients and exceptional results for all skin types.</p>
    </section>
    <section id="contact" class="products">
        <h2>Contact Us</h2>
        <p>Email: info@ellagantbeauty.com | Phone: (123) 456-7890</p>
    </section>
    <footer>
        <p>&copy; 2025 Ella'gant Beauty. All rights reserved.</p>
    </footer>
    <script>
        // Basic interactivity for add to cart (placeholder)
        document.querySelectorAll('.product button').forEach(button => {
            button.addEventListener('click', () => {
                alert('Product added to cart!');
            });
        });
    </script>
</body>
</html>
