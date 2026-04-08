<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Restaurant | Fresh & Fast</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        .hero-bg {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1514933651103-005eec06c04b?auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
            <h1 class="text-2xl font-bold text-orange-600">RESTAURANT NAME</h1>
            <div class="space-x-6">
                <a href="#home" class="hover:text-orange-600">Home</a>
                <a href="#menu" class="hover:text-orange-600">Menu</a>
                <a href="#order" class="bg-orange-600 text-white px-4 py-2 rounded-lg hover:bg-orange-700">Order Now</a>
            </div>
        </div>
    </nav>

    <header id="home" class="hero-bg h-[70vh] flex items-center justify-center text-center text-white">
        <div>
            <h2 class="text-5xl md:text-6xl font-bold mb-4">Delicious Food Delivered</h2>
            <p class="text-xl mb-8">Fresh ingredients, automated invoicing, and fast delivery.</p>
            <a href="#order" class="bg-orange-600 text-white px-8 py-3 rounded-full text-lg font-semibold hover:bg-orange-700 transition">Start Your Order</a>
        </div>
    </header>

    <section class="py-16 max-w-6xl mx-auto px-4 grid md:grid-cols-3 gap-8 text-center">
        <div class="p-6 bg-white rounded-xl shadow-sm">
            <i class="fas fa-utensils text-4xl text-orange-500 mb-4"></i>
            <h3 class="text-xl font-bold mb-2">Quality Food</h3>
            <p class="text-gray-600">We use only the freshest ingredients for every meal.</p>
        </div>
        <div class="p-6 bg-white rounded-xl shadow-sm">
            <i class="fas fa-file-invoice-dollar text-4xl text-orange-500 mb-4"></i>
            <h3 class="text-xl font-bold mb-2">Auto-Invoicing</h3>
            <p class="text-gray-600">Get an instant digital receipt sent to your email.</p>
        </div>
        <div class="p-6 bg-white rounded-xl shadow-sm">
            <i class="fas fa-shipping-fast text-4xl text-orange-500 mb-4"></i>
            <h3 class="text-xl font-bold mb-2">Fast Delivery</h3>
            <p class="text-gray-600">Track your order from our kitchen to your door.</p>
        </div>
    </section>

    <section id="order" class="py-16 bg-white">
        <div class="max-w-4xl mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-4">Place Your Order</h2>
            <p class="mb-10 text-gray-600">Select your favorite dishes below. Our system will automatically generate your invoice upon confirmation.</p>
            
            <div class="border-2 border-dashed border-gray-300 rounded-lg p-12 bg-gray-50">
                <p class="text-gray-500 italic mb-4">[Your Ordering Widget Will Appear Here]</p>
                <button class="bg-orange-600 text-white px-10 py-4 rounded font-bold uppercase tracking-widest shadow-lg">
                    See Menu & Order
                </button>
            </div>
            </div>
    </section>

    <footer class="bg-gray-900 text-white py-10 text-center">
        <p>&copy; 2026 Restaurant Name. Built with GitHub Pages.</p>
    </footer>

</body>
</html>
