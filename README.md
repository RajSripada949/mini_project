# mini_project
#Amazon clone project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon Clone</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #EAEDED;
        }

        header {
            background-color: #131921;
            color: white;
            padding: 10px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            margin-left: 20px;
        }

        .logo img {
            width: 100px;
        }

        .search-bar {
            display: flex;
            flex: 1;
            justify-content: center;
        }

        .search-bar input {
            width: 60%;
            padding: 10px;
            border: none;
            border-radius: 4px;
        }

        .search-bar button {
            padding: 10px;
            background-color: #febd69;
            border: none;
            border-radius: 0 4px 4px 0;
        }

        .nav-links {
            display: flex;
            margin-right: 20px;
        }

        .nav-links a {
            color: white;
            margin-left: 20px;
            text-decoration: none;
        }

        .banner {
            width: 100%;
            height: 300px;
            background-image: url('https://via.placeholder.com/1500x300');
            background-position: center;
            background-size: cover;
            margin: 20px 0;
        }

        .products {
            display: flex;
            justify-content: space-evenly;
            margin: 20px 0;
            flex-wrap: wrap;
        }

        .product {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            width: 250px;
            margin: 10px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .product img {
            width: 100%;
            height: 200px;
            object-fit: contain;
            margin-bottom: 15px;
        }

        .product-logo {
            width: 50px;
            height: auto;
            margin-bottom: 10px;
        }

        .product-title {
            font-size: 18px;
            margin-bottom: 10px;
        }

        .product-price {
            color: #b12704;
            margin-bottom: 10px;
        }

        footer {
            background-color: #131921;
            color: white;
            padding: 20px;
            text-align: center;
        }

        footer p {
            margin: 5px 0;
        }

        @media screen and (max-width: 768px) {
            .search-bar input {
                width: 80%;
            }

            .products {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>

<body>
    <header>
        <div class="logo">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" alt="Amazon Logo">
        </div>
        <div class="search-bar">
            <input type="text" placeholder="Search products...">
            <button>Search</button>
        </div>
        <div class="nav-links">
            <a href="#">Sign In</a>
            <a href="#">Orders</a>
            <a href="#">Cart</a>
        </div>
    </header>

    <section class="banner"></section>

    <section class="products">
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 1">
            <img src="https://via.placeholder.com/50" class="product-logo" alt="Product 1 Logo">
            <h3 class="product-title">Product 1</h3>
            <p class="product-price">$49.99</p>
            <p>Some description of product 1.</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 2">
            <img src="https://via.placeholder.com/50" class="product-logo" alt="Product 2 Logo">
            <h3 class="product-title">Product 2</h3>
            <p class="product-price">$99.99</p>
            <p>Some description of product 2.</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 3">
            <img src="https://via.placeholder.com/50" class="product-logo" alt="Product 3 Logo">
            <h3 class="product-title">Product 3</h3>
            <p class="product-price">$149.99</p>
            <p>Some description of product 3.</p>
        </div>
    </section>

    <footer>
        <p>Amazon Clone | Created by You</p>
        <p>&copy; 2024 All rights reserved</p>
    </footer>
</body>

</html>
