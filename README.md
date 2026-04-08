
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khan Kitchen & Culinary | Order Online</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        .hero-bg {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                        url('https://images.unsplash.com/photo-1559339352-11d035aa65de?auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-position: center;
        }
        .accent-gold { color: #D4AF37; }
        .bg-gold { background-color: #D4AF37; }
    </style>
</head>
<body class="bg-gray-50 text-gray-900 font-sans">

    <nav class="bg-white shadow-sm sticky top-0 z-50 border-b border-gray-100">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex flex-col">
                <span class="text-xl font-bold tracking-tight text-gray-900">KHAN KITCHEN</span>
                <span class="text-xs uppercase tracking-[0.2em] accent-gold font-semibold">& Culinary</span>
            </div>
            <div class="hidden md:flex space-x-8 text-sm font-medium uppercase tracking-wide">
                <a href="#home" class="hover:accent-gold transition">Home</a>
                <a href="#menu" class="hover:accent-gold transition">Our Menu</a>
                <a href="#order" class="bg-black text-white px-5 py-2 rounded hover:bg-gray-800 transition">Order Now</a>
            </div>
        </div>
    </nav>

    <header id="home" class="hero-bg h-[80vh] flex items-center justify-center text-center text-white px-4">
        <div class="max-w-3xl">
            <h2 class="text-5xl md:text-7xl font-serif mb-6">Exquisite Taste, <br>Delivered to You.</h2>
            <p class="text-lg md:text-xl mb-10 text-gray-300 font-light tracking-wide">Experience the finest culinary creations from Khan Kitchen. Order online for instant confirmation and automated invoicing.</p>
            <a href="#order" class="bg-gold text-white px-10 py-4 rounded shadow-2xl text-lg font-semibold hover:bg-yellow-600 transition duration-300">Place Your Order</a>
        </div>
    </header>

    <section class="py-20 max-w-6xl mx-auto px-6 grid md:grid-cols-3 gap-12 text-center">
        <div>
            <div class="w-16 h-16 bg-gray-100 rounded-full flex items-center justify-center mx-auto mb-6">
                <i class="fas fa-utensils text-2xl text-gray-800"></i>
            </div>
            <h3 class="text-xl font-bold mb-3">Gourmet Menu</h3>
            <p class="text-gray-500 leading-relaxed">Handcrafted dishes prepared with premium ingredients and culinary expertise.</p>
        </div>
        <div>
            <div class="w-16 h-16 bg-gray-100 rounded-full flex items-center justify-center mx-auto mb-6">
                <i class="fas fa-file-invoice text-2xl text-gray-800"></i>
            </div>
            <h3 class="text-xl font-bold mb-3">Auto-Invoice</h3>
            <p class="text-gray-500 leading-relaxed">Receive a professional digital invoice automatically as soon as your order is confirmed.</p>
        </div>
        <div>
            <div class="w-16 h-16 bg-gray-100 rounded-full flex items-center justify-center mx-auto mb-6">
                <i class="fas fa-clock text-2xl text-gray-800"></i>
            </div>
            <h3 class="text-xl font-bold mb-3">Swift Service</h3>
            <p class="text-gray-500 leading-relaxed">Our kitchen workflow is optimized for speed without compromising on quality.</p>
        </div>
    </section>

    <section id="order" class="py-24 bg-gray-100">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="text-4xl font-serif mb-4">Start Your Order</h2>
            <div class="w-20 h-1 bg-gold mx-auto mb-8"></div>
            <p class="mb-12 text-gray-600 max-w-2xl mx-auto">Browse our menu below. For every order, a detailed invoice will be sent to your registered email for your records.</p>
            
            <div class="bg-white p-2 md:p-10 rounded-2xl shadow-xl min-h-[400px] flex flex-col justify-center items-center">
                
                <div class="mb-6">
                    <i class="fas fa-shopping-basket text-5xl text-gray-200"></i>
                </div>
                
                <button class="bg-black text-white px-12 py-4 rounded-full font-bold uppercase tracking-widest hover:bg-gray-800 transition shadow-lg">
                    Open Digital Menu
                </button>
                
                <p class="mt-6 text-xs text-gray-400 uppercase tracking-widest">Powered by Khan Kitchen Ordering System</p>
            </div>
        </div>
    </section>

    <footer class="bg-white border-t border-gray-200 py-12">
        <div class="max-w-6xl mx-auto px-6 text-center">
            <div class="flex flex-col items-center mb-6">
                <span class="text-xl font-bold tracking-tight">KHAN KITCHEN</span>
                <span class="text-xs uppercase tracking-[0.2em] accent-gold font-semibold">& Culinary</span>
            </div>
            <p class="text-gray-400 text-sm">&copy; 2026 Khan Kitchen & Culinary. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
