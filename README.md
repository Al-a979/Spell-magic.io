<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spell - Luxurious Rune Jewelry</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #111;
            color: #fff;
        }
        header {
            background-color: #222;
            padding: 20px;
            text-align: center;
        }
        nav a {
            color: gold;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            text-align: center;
            padding: 100px 20px;
            background-image: url('luxury-rune-bg.jpg');
            background-size: cover;
            background-position: center;
        }
        .hero h1 {
            font-size: 3rem;
            color: gold;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .products {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 50px;
        }
        .product {
            background: #222;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            width: 250px;
        }
        .product img {
            width: 100%;
            border-radius: 5px;
        }
        .footer {
            text-align: center;
            padding: 20px;
            background: #222;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="#about">About</a>
            <a href="#shop">Shop</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <section class="hero">
        <h1>Spell - Mystical Rune Jewelry</h1>
        <p>Discover the magic of ancient runes crafted in gold and leather.</p>
    </section>
    <section class="products" id="shop">
        <div class="product">
            <img src="bracelet.jpg" alt="Gold Rune Bracelet">
            <h3>Gold Rune Bracelet</h3>
            <p>$250</p>
        </div>
        <div class="product">
            <img src="ring.jpg" alt="Rune Engraved Ring">
            <h3>Rune Engraved Ring</h3>
            <p>$180</p>
        </div>
        <div class="product">
            <img src="necklace.jpg" alt="Rune Pendant Necklace">
            <h3>Rune Pendant Necklace</h3>
            <p>$320</p>
        </div>
    </section>
    <footer class="footer">
        <p>&copy; 2025 Spell Jewelry. All Rights Reserved.</p>
    </footer>
</body>
</html>
