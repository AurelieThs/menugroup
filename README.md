# menugroup
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vespa Ristorante - Menu</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>
    
<header class="bg-danger text-white text-center py-3">
    <div class="container d-flex justify-content-between align-items-center">
        <h1 class="m-0">Vespa Ristorante 🇮🇹</h1>
        <a href="#" class="btn btn-light">Book a Table</a>
    </div>
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav mx-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Menu</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">About Us</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
</header>

<main class="container my-5">
    <h2 class="text-center">Our Exquisite Menu</h2>
    
    <!-- Section: Entrées (Positionnée au-dessus des pizzas) -->
    <section class="menu-category">
        <h3>🍤 Entrées</h3>
        <div class="d-flex justify-content-between flex-wrap">
            <div class="menu-item">
                <img src="https://th.bing.com/th/id/OIP.GcZVUF8tgzu-Pnp56RofYQHaLH?w=141&h=211&c=7&r=0&o=5&dpr=1.5&pid=1.7" alt="Image" height="120" width="120">
                <strong>Bruschetta</strong>
                <p>Toasted bread with garlic, tomatoes, basil, and olive oil.</p>
                <span class="text-danger fw-bold">€7</span>
            </div>
        </div>
    </section>
    
    <!-- Section: Pizzas -->
    <section class="menu-category">
        <h3>🍕 Pizzas</h3>
        <div class="d-flex justify-content-between flex-wrap">
            <div class="menu-item">
                <img src="https://th.bing.com/th/id/OIP.mrq9EI-sRaPx0JsrH87J3wHaHa?pid=ImgDet&w=178&h=178&c=7&dpr=1,5" alt="Image" height="120" width="120">
                <strong>Margherita</strong>
                <p>A timeless classic with fresh tomatoes, creamy mozzarella, and fragrant basil.</p> 
                <span class="text-danger fw-bold">€10</span>
            </div>
            <div class="menu-item">
                <img src="https://th.bing.com/th/id/OIP.DD_u-B4cTm8Oj_gGcbiRGwHaE8?w=242&h=180&c=7&r=0&o=5&dpr=1.5&pid=1.7" alt="Image" height="120" width="120">
                <strong>Vegetarian Delight</strong>
                <p>A colorful mix of roasted aubergines, zucchini, and bell peppers.</p>
                <span class="text-danger fw-bold">€12</span>
            </div>
        </div>
    </section>
    
    <!-- Section: Pasta (Positionnée sous les pizzas) -->
    <section class="menu-category">
        <h3>🍝 Pasta</h3>
        <div class="d-flex justify-content-between flex-wrap">
            <div class="menu-item">
                <img src="https://th.bing.com/th/id/OIP.jMLdCcFXJ6Ji9D97ueCYUAHaJQ?w=202&h=253&c=7&r=0&o=5&dpr=1.5&pid=1.7" alt="Image" height="120" width="120">
                <strong>Spaghetti Carbonara</strong>
                <p>A creamy blend of eggs, pancetta, and parmesan cheese.</p>
                <span class="text-danger fw-bold">€11</span>
            </div>
            <div class="menu-item">
                <img src="https://th.bing.com/th/id/OIP.33rVTEaS4Nv-vw0Tv7jxowHaHa?w=181&h=181&c=7&r=0&o=5&dpr=1.5&pid=1.7" alt="Image" height="120" width="120">
                <strong>Spaghetti Bolognese</strong>
                <p>Rich tomato sauce infused with minced beef and Italian herbs.</p>
                <span class="text-danger fw-bold">€11</span>
            </div>
        </div>
    </section>

    <!-- Section: Desserts (Positionnée sous les pâtes) -->
    <section class="menu-category">
        <h3>🍰 Desserts</h3>
        <div class="d-flex justify-content-between flex-wrap">
            <div class="menu-item">
                <img src="https://th.bing.com/th/id/OIP.-WaMpiGmUhiE-WQjeKv9SAHaFj?w=252&h=189&c=7&r=0&o=5&dpr=1.5&pid=1.7" alt="Image" height="120" width="120">
                <strong>Tiramisu</strong>
                <p>A rich Italian dessert made of layers of coffee-soaked ladyfingers, mascarpone cheese, and cocoa powder.</p>
                <span class="text-danger fw-bold">€6</span>
            </div>
        </div>
    </section>
</main>

<footer class="text-center bg-danger text-white py-3">
    <p>&copy; 2025 Vespa Ristorante - All rights reserved.</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

body {
    font-family: 'Poppins', sans-serif;
    background-color: #f8f8f8;
    margin: 0;
    padding: 0;
}

header {
    background-color: #d32f2f; 
    color: white;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 2.5rem;
}

header .btn {
    font-weight: bold;
}

nav {
    background-color: #333;
}

nav .nav-link {
    color: white;
    padding: 15px 20px;
}

nav .nav-link:hover {
    background-color: #d32f2f;
}

.menu-category {
    margin-bottom: 60px; 
}

.menu-category h3 {
    text-align: center;
    color: #d32f2f;
    font-weight: 600;
    margin-bottom: 20px;
}

.menu-item {
    width: 250px;
    text-align: center;
    margin: 15px;
    padding: 15px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.menu-item:hover {
    transform: translateY(-5px);
}

.menu-item img {
    width: 150px; 
    height: 150px;
    object-fit: cover;
    border-radius: 50%; 
    border: 4px solid #d32f2f;
    display: block;
    margin: 0 auto 10px;
}

.menu-item strong {
    display: block;
    margin-top: 10px;
    font-size: 18px;
    font-weight: bold;
}

p {
    font-size: 14px;
    color: #555;
    margin-top: 10px;
}

.text-danger {
    font-size: 16px;
}

.d-flex {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 40px; 
}

footer {
    background-color: #d32f2f;
    color: white;
    text-align: center;
    padding: 20px 0;
}
