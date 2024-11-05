# html-css-project
<!DOCTYPE html>
<html lang="en">
<head>
  <style>

   body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
}

header {
    background-color: #ff3f6d;
    color: white;
    padding: 20px;
    text-align: center;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.banner {
    background-color: #ffe4e1;
    padding: 50px 20px;
    text-align: center;
}

.shop-button {
    background-color: #ff3f6d;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.products {
    padding: 20px;
    text-align: center;
}

.product-card {
    display: inline-block;
    margin: 10px;
    padding: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    background-color: white;
    width: 200px;
}

.product-card img {
    max-width: 100%;
    height: auto;
}
footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: white;
}
.button{
    color: #a53fff;
}

  </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="project3.css">
    <title>Nykaa Fashion</title>
</head>
<body>
    <header>
        <div class="logo">Nykaa Fashion</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    
  <main>
        <section class="banner">
            <h1>Discover the Latest Trends</h1>
            <p>Shop the latest styles and trends in fashion.</p>
            <a href="#" class="shop-button">Shop Now</a>
        </section>
        
   <section class="products">
            <h2>Featured Products</h2>
            <div class="product-card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRC-p215KcK_rSTQAmqvDGYnqazWOefBTODxg&s">
                <h1>Women Indianwear</h1>
                <h3>Upto 75% off</h3>
                <p>Light up your look</p>
            </div>
            <div class="product-card">
                <IMG src="https://i.pinimg.com/736x/87/dd/0f/87dd0fa0fb41c56d35f6e04b156634a5.jpg">
                <h1>Men Indianwear</h1>
                <h3>Starting from $29.99</h3>
                <p>10% Instant Discount</p>
            </div>
            <div class="product-card">
                <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcTscppOF5UAlQ4FjM4cSW43s8IgjoZVnjFG9Wzo_YEKi7Ng0B4uoySCvIh9hiMPpzruKASxL7UDypctxRcuJU-mAONlveq0jMeaNbLeW7p0"alt="Product 4">
                <h2>Men Western</h2>
                <h4>Extra 20% off<h4>
                <p>Top Deals</p>
            </div>
            <div class="product-card">
                <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcQItB4ZlMmX67KvnJN5d-lJesF3Ev6olF-I7sfipFykHd7MLDOMy2h_IFrrUZ14KqDMJtVvtggeGEuQA0TexT7uwJrqDARpmgrPhf6bzQ5T52Y26O3Bq-ePig&usqp=CAE" alt="Product 3">
                <h1>Sneakers</h1>
                <h5>Shop Now</h5>
                <p>At lowest price</p>
            </div>
            <div class="product-card">
                <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcQIdaW51Us-IHT9uNB9n28FpVNp74P4BbxiKkkrdONM_Yd9sGdP3xNqJLm0y7ZUzsx7YrTcJd_k0QBMnt9Ko2XY_F4GFlRDnuYBjoS8lw2xc7NDI7X1IDxEAfc&usqp=CAE" alt="Product 3">
                <h1>Bags</h1>
                <h5>Hurry Up</h5>
                <p>Less products left</p>
            </div>
            <div class="product-card">
                <img SRC="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcTqluOOf-LJbFjUhba3JTi74zPzhdy9wP6AlkzxL927_YQEBYMJ6IS_IH8D2quctfMiRSjeS7DTotXbEizKrHmvAkoLEjVySWe9n4rjcVI9kkxIoH0ooTtCIA&usqp=CAE " alt="Product 3">
                <h2>Sugar Cosmetics</h2>
                <h5>Good Quality</h5>
                <p>Hurry Up</p>
            </div>
            <div class="product-card">
                <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcRbXBp1ewI8jvbNQ4SpuL2yvE_hwYYMcULZOqJrWr8BgnJn1hZ90ebgqTL2SB0kevmpSxhGf-AXvIZp6iVFOLM7rTKJMZAdpg&usqp=CAE" alt="Product 3">
                <h2>Smart Watches</h2>
                <h4>Buy 1 get 1 free</h4>
                <p></p>
            </div>
            <div class="product-card">
<h2>Jewelry</h2>
                <h4>Latest Discount</h4>
                </div>
            <div>
                <button>Home</button>
                <button>Categories</button>
                <button>Stay stylish</button>
                <button>Account</button>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy;</p>
    </footer>
</body>
</html>

