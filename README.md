## **Online Food Ordering System – Project Description (200 Words)**

The **Online Food Ordering System** is a web-based application designed to make food ordering easy, fast, and convenient for customers. This project allows users to browse different food items, view menus, check prices, select their favourite dishes, and place orders online without visiting a restaurant.

The system provides a user-friendly interface where customers can register, log in, explore available food items, add products to their shopping cart, and confirm their orders. It helps customers save time and makes the food ordering process simple and efficient.

The application also includes an admin section to manage food items, update prices, view customer details, and monitor orders. Customers can check their order details and track the status of their orders, depending on the system's implemented features.

The main objective of this project is to reduce manual work, improve customer convenience, and provide an organized method of managing food orders. It helps restaurants handle customer orders more efficiently and improves overall service quality.

This project is useful for restaurants, hotels, and food delivery businesses. It demonstrates the practical use of web development technologies and database management in developing a real-world application.# onlinefoodorder
The Online Food Ordering System is a web-based application that allows users to browse food items, view menus, add items to their cart, and place orders online. It provides a simple and user-friendly interface for customers to order food conveniently. The system helps manage food orders, customer details, and payments efficiently.
online-food-ordering-system/
│
├── index.html
├── style.css
└── script.js
<!DOCTYPE html>
<html>
<head>
    <title>Online Food Ordering System</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>🍕 Online Food Ordering</h1>
    <p>Order Your Favourite Food Online!</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#cart">Cart</a>
</nav>

<section id="home">
    <h2>Welcome to Food Express</h2>
    <p>Delicious food delivered to your doorstep.</p>
</section>

<section id="menu">
    <h2>Our Food Menu</h2>

    <div class="food-container">

        <div class="food">
            <h3>Pizza</h3>
            <p>Price: ₹150</p>
            <button onclick="addToCart('Pizza',150)">Add to Cart</button>
        </div>

        <div class="food">
            <h3>Burger</h3>
            <p>Price: ₹100</p>
            <button onclick="addToCart('Burger',100)">Add to Cart</button>
        </div>

        <div class="food">
            <h3>Biryani</h3>
            <p>Price: ₹180</p>
            <button onclick="addToCart('Biryani',180)">Add to Cart</button>
        </div>

        <div class="food">
            <h3>Dosa</h3>
            <p>Price: ₹60</p>
            <button onclick="addToCart('Dosa',60)">Add to Cart</button>
        </div>

    </div>
</section>

<section id="cart">
    <h2>Shopping Cart</h2>
    <ul id="cart-items"></ul>
    <h3>Total: ₹<span id="total">0</span></h3>
    <button onclick="placeOrder()">Place Order</button>
</section>

<footer>
    <p>© 2026 Online Food Ordering System</p>
</footer>

<script src="script.js"></script>
</body>
</html>
