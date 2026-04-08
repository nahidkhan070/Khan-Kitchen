
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khan Kitchen & Culinary | Premium Dining</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root { --fiery-gold: #FF9900; --logo-gold: #D4AF37; }
        body { font-family: 'Inter', sans-serif; background-color: #050505; color: white; scroll-behavior: smooth; overflow-x: hidden; }
        .font-serif { font-family: 'Cinzel', serif; }
        .gold-button { border: 1px solid var(--fiery-gold); color: var(--fiery-gold); transition: all 0.4s ease; text-transform: uppercase; letter-spacing: 0.2em; }
        .gold-button:hover { background-color: var(--fiery-gold); color: black; box-shadow: 0 0 25px rgba(255, 153, 0, 0.5); }
        .menu-grid { border-top: 1px solid rgba(212, 175, 55, 0.1); }
        .map-container iframe { filter: grayscale(100%) invert(90%) contrast(90%); }
    </style>
</head>
<body>

    <nav class="fixed top-0 left-0 w-full z-50 bg-[#050505]/95 backdrop-blur-md border-b border-white/5">
        <div class="max-w-7xl mx-auto px-6 py-3 flex justify-between items-center">
            <img src="logo.png" alt="Khan Kitchen Logo" class="h-12 object-contain">
            <div class="hidden md:flex space-x-8 text-[10px] font-bold tracking-widest text-gray-400">
                <a href="#home" class="hover:text-white transition">HOME</a>
                <a href="#menu" class="hover:text-white transition">MENU</a>
                <a href="#location" class="hover:text-white transition">LOCATION</a>
                <a href="#order" class="text-fiery-gold">ORDER ONLINE</a>
            </div>
        </div>
    </nav>

    <header id="home" class="relative h-[80vh] flex items-center justify-center text-center overflow-hidden">
        <div class="absolute inset-0 z-0">
            <video autoplay muted loop playsinline class="w-full h-full object-cover opacity-40">
                <source src="https://assets.mixkit.co/videos/preview/mixkit-grilling-meat-and-vegetables-on-a-flaming-grill-4235-large.mp4" type="video/mp4">
            </video>
            <div class="absolute inset-0 bg-gradient-to-b from-transparent to-[#050505]"></div>
        </div>
        <div class="relative z-10 px-6">
            <img src="logo.png" alt="Khan Culinary" class="w-auto h-64 md:h-80 mx-auto drop-shadow-2xl">
            <a href="#order" class="gold-button mt-12 inline-block px-12 py-4 text-xs font-bold">Reserve Your Taste</a>
        </div>
    </header>

    <section id="menu" class="py-24 max-w-6xl mx-auto px-6">
        <div class="text-center mb-16">
            <h2 class="text-4xl font-serif text-logo-gold">The Culinary Gallery</h2>
            <div class="w-24 h-px bg-fiery-gold/30 mx-auto mt-4"></div>
        </div>

        <div class="grid md:grid-cols-2 gap-16">
            <div>
                <h3 class="text-xl font-serif text-fiery-gold mb-8 flex items-center tracking-widest">
                    <span class="mr-4">01.</span> THE GRILL STATION
                </h3>
                <div class="space-y-8">
                    <div class="flex justify-between border-b border-white/5 pb-4">
                        <div><h4 class="font-bold uppercase text-sm">Reshmi Malai Kebab</h4><p class="text-xs text-gray-500 mt-1">Chicken in silk-cream marinade</p></div>
                        <span class="text-logo-gold">$18</span>
                    </div>
                    <div class="flex justify-between border-b border-white/5 pb-4">
                        <div><h4 class="font-bold uppercase text-sm">Hariyali Tikka</h4><p class="text-xs text-gray-500 mt-1">Fresh mint & coriander infused chicken</p></div>
                        <span class="text-logo-gold">$16</span>
                    </div>
                    <div class="flex justify-between border-b border-white/5 pb-4">
                        <div><h4 class="font-bold uppercase text-sm">Mutton Seekh Kebab</h4><p class="text-xs text-gray-500 mt-1">Hand-minced with 12 house spices</p></div>
                        <span class="text-logo-gold">$22</span>
                    </div>
                </div>
            </div>

            <div>
                <h3 class="text-xl font-serif text-fiery-gold mb-8 flex items-center tracking-widest">
                    <span class="mr-4">02.</span> ROYAL CURRIES
                </h3>
                <div class="space-y-8">
                    <div class="flex justify-between border-b border-white/5 pb-4">
                        <div><h4 class="font-bold uppercase text-sm">Butter Chicken Gold</h4><p class="text-xs text-gray-500 mt-1">Smoked butter & velvet tomato gravy</p></div>
                        <span class="text-logo-gold">$20</span>
                    </div>
                    <div class="flex justify-between border-b border-white/5 pb-4">
                        <div><h4 class="font-bold uppercase text-sm">Peshawari Mutton Karahi</h4><p class="text-xs text-gray-500 mt-1">Wok-tossed with ginger & black pepper</p></div>
                        <span class="text-logo-gold">$24</span>
                    </div>
                    <div class="flex justify-between border-b border-white/5 pb-4">
                        <div><h4 class="font-bold uppercase text-sm">Paneer Lababdar</h4><p class="text-xs text-gray-500 mt-1">Cottage cheese in a chunky onion-tomato base</p></div>
                        <span class="text-logo-gold">$15</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="location" class="py-24 bg-black/50 border-y border-white/5">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div class="map-container rounded-2xl overflow-hidden h-[400px] border border-white/10">
                <iframe 
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d116834.00977794302!2d90.34928424335938!3d23.78033745!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755c703f83138b1%3A0x63351d3844f77c3!2sGazipur!5e0!3m2!1sen!2sbd!4v1712574000000!5m2!1sen!2sbd" 
                    width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy">
                </iframe>
            </div>
            <div class="text-center md:text-left space-y-6">
                <h2 class="text-3xl font-serif text-logo-gold">Visit the Kitchen</h2>
                <div class="space-y-4">
                    <p class="flex items-center justify-center md:justify-start text-gray-400">
                        <i class="fas fa-map-marker-alt text-fiery-gold mr-4"></i>
                        Gazipur City Center, Dhaka Division, Bangladesh
                    </p>
                    <p class="flex items-center justify-center md:justify-start text-gray-400">
                        <i class="fas fa-phone-alt text-fiery-gold mr-4"></i>
                        +880 1XXX-XXXXXX
                    </p>
                    <p class="flex items-center justify-center md:justify-start text-gray-400">
                        <i class="fas fa-clock text-fiery-gold mr-4"></i>
                        Open Daily: 12:00 PM - 11:00 PM
                    </p>
                </div>
                <div class="pt-6">
                    <a href="https://maps.google.com" target="_blank" class="text-xs font-bold tracking-widest text-fiery-gold hover:underline">GET DIRECTIONS →</a>
                </div>
            </div>
        </div>
    </section>

    <section id="order" class="py-32 bg-black text-center">
        <div class="max-w-2xl mx-auto px-6">
            <h2 class="text-4xl font-serif mb-6 italic">Khan Culinary At Home</h2>
            <p class="text-gray-500 mb-12 uppercase tracking-[0.3em] text-[10px]">Instant Invoice • Professional Delivery • Secure Checkout</p>
            <a href="https://khan-kitchen-culinary.square.site" target="_blank" class="gold-button inline-block px-16 py-5 text-sm font-bold">
                Order Online
            </a>
        </div>
    </section>

    <footer class="py-12 border-t border-white/5 text-center">
        <img src="logo.png" alt="Logo" class="h-10 mx-auto opacity-50 mb-6">
        <p class="text-[10px] text-gray-600 tracking-[0.5em] uppercase">&copy; 2026 Khan Kitchen & Culinary. Excellence served daily.</p>
    </footer>

</body>
</html>
