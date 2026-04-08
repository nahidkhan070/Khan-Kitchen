
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khan Kitchen & Culinary | Gourmet Menu</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        .hero-bg {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                        url('https://images.unsplash.com/photo-1555939594-58d7cb561ad1?auto=format&fit=crop&w=1920&q=80');
            background-size: cover; background-position: center;
        }
        .accent-gold { color: #D4AF37; }
        .bg-gold { background-color: #D4AF37; }
        .food-card:hover img { transform: scale(1.05); transition: 0.5s; }
        .food-card img { transition: 0.5s; }
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
                <a href="#home" class="hover:accent-gold">Home</a>
                <a href="#menu" class="hover:accent-gold">Menu</a>
                <a href="#order" class="bg-black text-white px-5 py-2 rounded hover:bg-gray-800 transition">Order Now</a>
            </div>
        </div>
    </nav>

    <header id="home" class="hero-bg h-[60vh] flex items-center justify-center text-center text-white px-4">
        <div>
            <h2 class="text-5xl md:text-6xl font-serif mb-4">Taste the Tradition</h2>
            <p class="text-lg text-gray-300 tracking-widest uppercase">Kebabs • Curries • Perfection</p>
        </div>
    </header>

    <section id="menu" class="py-20 max-w-7xl mx-auto px-6">
        <div class="text-center mb-16">
            <h2 class="text-4xl font-serif mb-2">Our Culinary Highlights</h2>
            <p class="text-gray-500 italic">Freshly prepared, instantly invoiced.</p>
        </div>

        <h3 class="text-2xl font-bold mb-8 flex items-center"><span class="bg-gold w-8 h-1 mr-3"></span> Grilled Kebabs</h3>
        <div class="grid md:grid-cols-3 gap-8 mb-16">
            
            <div class="food-card bg-white rounded-xl shadow-md overflow-hidden">
                <div class="h-48 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1599487488170-d11ec9c172f0?auto=format&fit=crop&w=800&q=80" alt="Seekh Kebab" class="w-full h-full object-cover">
                </div>
                <div class="p-6">
                    <div class="flex justify-between items-center mb-2">
                        <h4 class="font-bold text-xl">Seekh Kebab</h4>
                        <span class="accent-gold font-bold">$14.50</span>
                    </div>
                    <p class="text-gray-600 text-sm">Spiced minced mutton skewers grilled to a smoky perfection.</p>
                </div>
            </div>

            <div class="food-card bg-white rounded-xl shadow-md overflow-hidden">
                <div class="h-48 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1633383718081-22ac93e3dbf1?auto=format&fit=crop&w=800&q=80" alt="Reshmi Kebab" class="w-full h-full object-cover">
                </div>
                <div class="p-6">
                    <div class="flex justify-between items-center mb-2">
                        <h4 class="font-bold text-xl">Reshmi Kebab</h4>
                        <span class="accent-gold font-bold">$12.99</span>
                    </div>
                    <p class="text-gray-600 text-sm">Silky smooth chicken pieces marinated in cream and mild spices.</p>
                </div>
            </div>

            <div class="food-card bg-white rounded-xl shadow-md overflow-hidden">
                <div class="h-48 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1628294895950-9805252327bc?auto=format&fit=crop&w=800&q=80" alt="Bihari Kebab" class="w-full h-full object-cover">
                </div>
                <div class="p-6">
                    <div class="flex justify-between items-center mb-2">
                        <h4 class="font-bold text-xl">Bihari Kebab</h4>
                        <span class="accent-gold font-bold">$15.99</span>
                    </div>
                    <p class="text-gray-600 text-sm">Traditional beef strips with a tender, melt-in-your-mouth texture.</p>
                </div>
            </div>
        </div>

        <h3 class="text-2xl font-bold mb-8 flex items-center"><span class="bg-gold w-8 h-1 mr-3"></span> Signature Curries</h3>
        <div class="grid md:grid-cols-3 gap-8">
            
            <div class="food-card bg-white rounded-xl shadow-md overflow-hidden">
                <div class="h-48 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1588166524941-3bf61a9c41db?auto=format&fit=crop&w=800&q=80" alt="Butter Chicken" class="w-full h-full object-cover">
                </div>
                <div class="p-6">
                    <div class="flex justify-between items-center mb-2">
                        <h4 class="font-bold text-xl">Butter Chicken</h4>
                        <span class="accent-gold font-bold">$13.99</span>
                    </div>
                    <p class="text-gray-600 text-sm">Rich, creamy tomato gravy with tender grilled chicken chunks.</p>
                </div>
            </div>

            <div class="food-card bg-white rounded-xl shadow-md overflow-hidden">
                <div class="h-48 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1545244603-013988f6a39d?auto=format&fit=crop&w=800&q=80" alt="Mutton Rogan Josh" class="w-full h-full object-cover">
                </div>
                <div class="p-6">
                    <div class="flex justify-between items-center mb-2">
                        <h4 class="font-bold text-xl">Rogan Josh</h4>
                        <span class="accent-gold font-bold">$16.50</span>
                    </div>
                    <p class="text-gray-600 text-sm">A classic Kashmiri mutton curry cooked with aromatic spices.</p>
                </div>
            </div>

            <div class="food-card bg-white rounded-xl shadow-md overflow-hidden">
                <div class="h-48 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1631452180519-c014fe946bc7?auto=format&fit=crop&w=800&q=80" alt="Dal Makhani" class="w-full h-full object-cover">
                </div>
                <div class="p-6">
                    <div class="flex justify-between items-center mb-2">
                        <h4 class="font-bold text-xl">Dal Makhani</h4>
                        <span class="accent-gold font-bold">$10.99</span>
                    </div>
                    <p class="text-gray-600 text-sm">Black lentils slow-cooked overnight with butter and cream.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="order" class="py-24 bg-gray-100">
        <div class="max-w-xl mx-auto px-6 text-center bg-white p-12 rounded-3xl shadow-xl">
            <h2 class="text-3xl font-serif mb-4">Ready to Eat?</h2>
            <p class="text-gray-500 mb-8">Click below to place your order. Our system generates your <strong>auto-invoice</strong> instantly for a seamless experience.</p>
            
            <button class="bg-black text-white px-12 py-4 rounded-full font-bold uppercase tracking-widest hover:scale-105 transition transform">
                Order Online Now
            </button>
        </div>
    </section>

    <footer class="bg-white border-t py-12 text-center">
        <p class="font-bold tracking-tight">KHAN KITCHEN & CULINARY</p>
        <p class="text-gray-400 text-xs mt-2 uppercase tracking-widest">&copy; 2026 Professional Dining Experience</p>
    </footer>

</body>
</html>
