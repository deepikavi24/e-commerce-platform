# ecommerceplatform
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My eCommerce Store</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <h1>My eCommerce Store</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#cart">Cart</a></li>
                    <li><a href="#checkout">Checkout</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Home Section -->
        <section id="home">
            <div class="container">
                <h2>Welcome to our Store</h2>
                <p>Explore our wide range of products.</p>
            </div>
        </section>

        <!-- Products Section -->
        <section id="products">
            <div class="container">
                <h2>Our Products</h2>
                <div class="product">
                    <img src="product1.jpg" alt="Product 1">
                    <h3>Product 1</h3>
                    <p>Description of Product 1.</p>
                    <p>$99.99</p>
                    <button>Add to Cart</button>
                </div>
                <div class="product">
                    <img src="product2.jpg" alt="Product 2">
                    <h3>Product 2</h3>
                    <p>Description of Product 2.</p>
                    <p>$149.99</p>
                    <button>Add to Cart</button>
                </div>
                <!-- Add more products as needed -->
            </div>
        </section>

        <!-- Cart Section -->
        <section id="cart">
            <div class="container">
                <h2>Your Shopping Cart</h2>
                <div class="cart-item">
                    <img src="product1.jpg" alt="Product 1">
                    <div>
                        <h3>Product 1</h3>
                        <p>$99.99</p>
                    </div>
                    <div>
                        <input type="number" value="1">
                        <button>Update</button>
                    </div>
                </div>
                <!-- Repeat for each item in the cart -->
                <div class="total">
                    <h3>Total: $99.99</h3>
                    <button>Proceed to Checkout</button>
                </div>
            </div>
        </section>

        <!-- Checkout Section -->
        <section id="checkout">
            <div class="container">
                <h2>Checkout</h2>
                <form>
                    <label for="name">Name:</label>
                    <input type="text" id="name" required>
                    
                    <label for="email">Email:</label>
                    <input type="email" id="email" required>
                    
                    <label for="address">Address:</label>
                    <textarea id="address" rows="4" required></textarea>
                    
                    <button type="submit">Place Order</button>
                </form>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 My eCommerce Store. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
