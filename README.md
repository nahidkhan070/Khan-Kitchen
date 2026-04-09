
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khan Kitchen & Culinary | Official Site</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root { --fiery-gold: #FF9900; --logo-gold: #D4AF37; }
        body { font-family: 'Inter', sans-serif; background-color: #050505; color: white; scroll-behavior: smooth; overflow-x: hidden; }
        .font-serif { font-family: 'Cinzel', serif; }
        
        /* Gold Button Styling */
        .gold-button { border: 1px solid var(--fiery-gold); color: var(--fiery-gold); transition: all 0.4s ease; text-transform: uppercase; letter-spacing: 0.2em; }
        .gold-button:hover { background-color: var(--fiery-gold); color: black; box-shadow: 0 0 25px rgba(255, 153, 0, 0.6); transform: scale(1.05); }
        
        /* Splash Card Animation */
        .splash-card { position: relative; overflow: hidden; border-radius: 12px; height: 350px; border: 1px solid rgba(255,153,0,0.1); }
        .splash-card img { width: 100%; height: 100%; object-fit: cover; transition: transform 1.2s ease; filter: brightness(60%) contrast(110%); }
        .splash-card:hover img { transform: scale(1.15); filter: brightness(80%); }
        .splash-overlay { position: absolute; bottom: 0; left: 0; width: 100%; padding: 30px; background: linear-gradient(transparent, rgba(0,0,0,0.95)); }
        
        /* Smoke Texture */
        .smoke-bg { background-image: url('https://www.transparenttextures.com/patterns/black-linen.png'); }
    </style>
</head>
<body class="smoke-bg">

    <nav class="fixed top-0 left-0 w-full z-50 bg-[#050505]/90 backdrop-blur-lg border-b border-white/5 px-6 py-3 flex justify-between items-center">
        <img src="logo.png" alt="Khan Kitchen Logo" class="h-12 object-contain">
        <div class="hidden md:flex space-x-8 text-[10px] font-bold tracking-[0.4em] text-gray-400">
            <a href="#home" class="hover:text-fiery-gold transition">HOME</a>
            <a href="#menu" class="hover:text-fiery-gold transition">KEBAB GALLERY</a>
            <a href="#location" class="hover:text-fiery-gold transition">LOCATION</a>
            <a href="https://khan-kitchen-culinary.square.site/" target="_blank" class="text-fiery-gold border-b border-fiery-gold/30 pb-1">ORDER ONLINE</a>
        </div>
    </nav>

    <header id="home" class="relative h-screen flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0 bg-black/40 z-10"></div>
        <video autoplay muted loop playsinline class="absolute inset-0 w-full h-full object-cover opacity-50">
            <source src="https://assets.mixkit.co/videos/preview/mixkit-grilling-meat-and-vegetables-on-a-flaming-grill-4235-large.mp4" type="video/mp4">
        </video>
        <div class="relative z-20 text-center px-6">
            <img src="logo.png" alt="Khan Culinary" class="w-auto h-64 md:h-96 mx-auto drop-shadow-[0_0_35px_rgba(255,153,0,0.3)] animate-pulse" style="animation-duration: 4s;">
            <div class="mt-8">
                <a href="https://khan-kitchen-culinary.square.site/" target="_blank" class="gold-button inline-block px-12 py-4 text-xs font-bold">
                    Start Your Order
                </a>
            </div>
        </div>
    </header>

    <section id="menu" class="py-32 max-w-7xl mx-auto px-6">
        <div class="text-center mb-24">
            <h2 class="text-5xl font-serif text-logo-gold tracking-widest uppercase">The Kebab Collection</h2>
            <div class="w-20 h-1 bg-fiery-gold mx-auto mt-6"></div>
        </div>

        <div class="grid md:grid-cols-3 gap-8 mb-24">
            <div class="splash-card">
                <img src="https://images.unsplash.com/photo-1599487488170-d11ec9c172f0?auto=format&fit=crop&w=800&q=80">
                <div class="splash-overlay">
                    <h4 class="font-serif text-fiery-gold text-xl tracking-widest">TRADITIONAL SEEKH</h4>
                    <p class="text-xs text-gray-400 mt-2 uppercase tracking-widest">Chicken • Beef • Mutton</p>
                </div>
            </div>
            <div class="splash-card mt-0 md:mt-12">
                <img src="https://images.unsplash.com/photo-1633383718081-22ac93e3dbf1?auto=format&fit=crop&w=800&q=80">
                <div class="splash-overlay">
                    <h4 class="font-serif text-fiery-gold text-xl tracking-widest">BOTI MASTERPIECE</h4>
                    <p class="text-xs text-gray-400 mt-2 uppercase tracking-widest">Malai Chicken • Reshmi Kebab</p>
                </div>
            </div>
            <div class="splash-card">
                <img src="https://images.unsplash.com/photo-1561651823-34feb02250e4?auto=format&fit=crop&w=800&q=80">
                <div class="splash-overlay">
                    <h4 class="font-serif text-fiery-gold text-xl tracking-widest">GLOBAL FUSION</h4>
                    <p class="text-xs text-gray-400 mt-2 uppercase tracking-widest">Doner • Adana • Shish Taouk</p>
                </div>
            </div>
        </div>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-x-16 gap-y-10 border-t border-white/10 pt-20">
            <div class="group border-b border-white/5 pb-4"><div class="flex justify-between font-bold text-xs tracking-widest"><span>CHICKEN SEEKH KEBAB</span><span class="text-fiery-gold">14</span></div></div>
            <div class="group border-b border-white/5 pb-4"><div class="flex justify-between font-bold text-xs tracking-widest"><span>BEEF SEEKH KEBAB</span><span class="text-fiery-gold">16</span></div></div>
            <div class="group border-
