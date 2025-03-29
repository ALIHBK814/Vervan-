# Vervan-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vervan - Perfumes Gallery</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Vervan</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#products">Products</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About Us</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="text-center py-5">
        <div class="container">
            <h1>Welcome to Vervan</h1>
            <p>Your Destination for Premium Perfumes</p>
            <a href="#products" class="btn btn-primary">Explore Our Collection</a>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Our Perfumes</h2>
            <div class="row">
                <!-- Product 1: IDEAL INTENSE -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://share.icloud.com/photos/0f6IadCRqjqKeGyw7Z4Rj-x3w" class="card-img-top" alt="IDEAL INTENSE">
                        <div class="card-body">
                            <h5 class="card-title">IDEAL INTENSE</h5>
                            <p class="card-text">
                                A magical blend of red berries, warm vanilla, French jasmine, creamy musk, and sandalwood. 
                                Perfect for women who love elegance and luxury.
                            </p>
                            <p class="card-text"><strong>Price: 150 LYD</strong></p>
                            <a href="https://wa.me/your-phone-number" class="btn btn-primary" target="_blank">Order Now via WhatsApp</a>
                        </div>
                    </div>
                </div>
                <!-- Add more products here -->
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-4">About Us</h2>
            <p>Vervan is a premier perfumes gallery store dedicated to providing high-quality fragrances for every occasion. We believe in the power of scent to enhance your personality and leave a lasting impression.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Your Name">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Your Email">
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2023 Vervan. All rights reserved.</p>
        <a href="https://www.facebook.com/your-facebook-page" target="_blank" class="text-white">Follow us on Facebook</a>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
}

.navbar-brand {
    font-weight: bold;
    color: #333;
}

.card {
    transition: transform 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

footer {
    margin-top: 50px;
}
