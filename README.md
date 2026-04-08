
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
            background-size: cover; background-position: center;
        }
        .accent-gold { color: #D4AF37; }
        .bg-gold { background-color: #D4AF37; }
        .menu-card:hover { transform: translateY(-5px); transition: 0.3s; }
    </style>
</head>
<body class="bg-gray-50 text-gray-900 font-sans">

    <nav class="bg-white shadow-sm sticky top-0 z-50 border-b border-gray-100">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex flex-col text-left">
                <span class="text-xl font-bold tracking-tight text-gray-900 leading-tight">KHAN KITCHEN</span>
                <span class="text-xs uppercase tracking-[0.2em] accent-gold font-semibold leading-tight">& Culinary</span>
            </div>
            <div class="hidden md:flex space-x-8 text-sm font-medium uppercase tracking-wide">
                <a href="#home" class="hover:accent-gold">Home</a>
                <a href="#menu" class="hover:accent-gold">Our Menu</a>
                <a href="#order" class="bg-black text-white px-5 py-2 rounded hover:bg-gray-800">Order Now</a>
            </div>
        </div>
    </nav>

    <header id="home" class="hero-bg h-[70vh] flex items-center justify-center text-center text-white px-4">
        <div class="max-w-3xl">
            <h2 class="text-5xl md:text-7xl font-serif mb-6">Exquisite Taste.</h2>
            <p class="text-lg md:text-xl mb-10 text-gray-300 font-light tracking-wide">Premium Kebab & Authentic Curry. Order online for instant auto-invoicing.</p>
            <a href="#order" class="bg-gold text-white px-10 py-4 rounded shadow-2xl text-lg font-semibold hover:bg-yellow-600 transition duration-300">Start Your Order</a>
        </div>
    </header>

    <section id="menu" class="py-20 max-w-6xl mx-auto px-6">
        <div class="text-center mb-16">
            <h2 class="text-4xl font-serif">Signature Dishes</h2>
            <div class="w-20 h-1 bg-gold mx-auto mt-4 mb-2"></div>
            <p class="text-gray-500 italic">Chef's special selection</p>
        </div>

        <div class="grid md:grid-cols-2 gap-12">
            <div>
                <h3 class="text-2xl font-bold border-b-2 border-gray-100 pb-3 mb-6"><i class="fas fa-fire-alt accent-gold mr-2"></i> The Kebab Grill</h3>
                
                <div class="space-y-6">
                    <div class="flex justify-between items-start">
                        <div>
                            <h4 class="font-bold text-lg">Reshmi Malai Kebab</h4>
                            <p class="text-sm text-gray-500">Tender chicken pieces marinated in cream, cheese, and mild spices.</p>
                        </div>
                        <span class="font-bold text-gold">$12.99</span>
                    </div>
                    <div class="flex justify-between items-start">
                        <div>
                            <h4 class="font-bold text-lg">Seekh Kebab (Mutton)</h4>
                            <p class="text-sm text-gray-500">Minced mutton skewers seasoned with fresh herbs and grilled in tandoor.</p>
                        </div>
                        <span class="font-bold text-gold">$14.50</span>
                    </div>
                    <div class="flex justify-between items-start">
                        <div>
                            <h4 class="font-bold text-lg">Khan Special Bihari Kebab</h4>
                            <p class="text-sm text-gray-500">Traditional spicy beef strips smoked to perfection.</p>
                        </div>
                        <span class="font-bold text-gold">$15.99</span>
                    </div>
                </div>
            </div>

            <div>
                <h3 class="text-2xl font-bold border-b-2 border-gray-100 pb-3 mb-6"><i class="fas fa-bowl-hot accent-gold mr-2"></i> Authentic Curries</h3>
                
                <div class="space-y-6">
                    <div class="flex justify-between items-start">
                        <div>
                            <h4 class="font-bold text-lg">Butter Chicken (Murgh Makhani)</h4>
                            <p class="text-sm text-gray-500">Classic tomato-based creamy gravy with succulent chicken chunks.</p>
                        </div>
                        <span class="font-
