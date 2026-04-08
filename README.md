
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khan Kitchen & Culinary | The Kebab Collection</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root { --fiery-gold: #FF9900; --logo-gold: #D4AF37; }
        body { font-family: 'Inter', sans-serif; background-color: #050505; color: white; scroll-behavior: smooth; overflow-x: hidden; }
        .font-serif { font-family: 'Cinzel', serif; }
        
        .gold-button { border: 1px solid var(--fiery-gold); color: var(--fiery-gold); transition: all 0.4s ease; text-transform: uppercase; letter-spacing: 0.2em; }
        .gold-button:hover { background-color: var(--fiery-gold); color: black; box-shadow: 0 0 25px rgba(255, 153, 0, 0.5); }
        
        /* Image Splash Effect */
        .splash-card { position: relative; overflow: hidden; border-radius: 8px; height: 300px; }
        .splash-card img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.8s ease; filter: brightness(70%); }
        .splash-card:hover img { transform: scale(1.1); filter: brightness(90%); }
        .splash-overlay { position: absolute; bottom: 0; left: 0; width: 100%; padding: 20px; background: linear-gradient(transparent, rgba(0,0,0,0.9)); }
    </style>
</head>
<body>

    <nav class="fixed top-0 left-0 w-full z-50 bg-[#050505]/95 backdrop-blur-md border-b border-white/5 px-6 py-3 flex justify-between items-center">
        <img src="logo.png" alt="Khan Kitchen Logo" class="h-10 object-contain">
        <div class="hidden md:flex space-x-8 text-[10px] font-bold tracking-[0.3em] text-gray-400">
            <a href="#home" class="hover:text-white transition">HOME</a>
            <a href="#menu" class="hover:text-white transition">KEBAB MENU</a>
            <a href="#location" class="hover:text-white transition">LOCATION</a>
            <a href="#order" class="text-fiery-gold">ORDER ONLINE</a>
        </div>
    </nav>

    <header id="home" class="relative h-[60vh] flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-b from-black/20 to-[#050505] z-10"></div>
        <img src="https://images.unsplash.com/photo-1544025162-d76694265947?auto=format&fit=crop&w=1920&q=80" class="absolute inset-0 w-full h-full object-cover opacity-30">
        <div class="relative z-20 text-center">
            <img src="logo.png" alt="Khan Culinary" class="w-auto h-56 md:h-72 mx-auto drop-shadow-2xl">
            <p class="text-fiery-gold font-serif tracking-[0.4em] mt-4 uppercase text-sm">The Master of Grills</p>
        </div>
    </header>

    <section id="menu" class="py-24 max-w-7xl mx-auto px-6">
        <div class="text-center mb-20">
            <h2 class="text-5xl font-serif text-logo-gold">The Kebab Collection</h2>
            <p class="text-gray-500 mt-4 uppercase tracking-widest text-xs italic">15 Signature Masterpieces</p>
        </div>

        <h3 class="text-2xl font-serif text-fiery-gold mb-10 tracking-[0.2em] border-l-4 border-fiery-gold pl-4">Traditional Charcoal Grills</h3>
        <div class="grid md:grid-cols-3 gap-8 mb-20">
            <div class="splash-card">
                <img src="https://images.unsplash.com/photo-1599487488170-d11ec9c172f0?auto=format&fit=crop&w=800&q=80" alt="Seekh Kebabs">
                <div class="splash-overlay">
                    <h4 class="font-bold text-lg">THE SEEKH TRIO</h4>
                    <p class="text-xs text-gray-400 italic">Chicken • Beef • Mutton Seekh</p>
                </div>
            </div>
            <div class="splash-card md:mt-12">
                <img src="https://images.unsplash.com/photo-1633383718081-22ac93e3dbf1?auto=format&fit=crop&w=800&q=80" alt="Boti Kebabs">
                <div class="splash-overlay">
                    <h4 class="font-bold text-lg">BOTI SPECIALS</h4>
                    <p class="text-xs text-gray-400 italic">Chicken Boti • Beef Boti</p>
                </div>
            </div>
            <div class="splash-card">
                <img src="https://images.unsplash.com/photo-1628294895950-9805252327bc?auto=format&fit=crop&w=800&q=80" alt="Reshmi/Malai">
                <div class="splash-overlay">
                    <h4 class="font-bold text-lg">CREAM & SILK</h4>
                    <p class="text-xs text-gray-400 italic">Malai Chicken • Reshmi Kebab</p>
                </div>
            </div>
        </div>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-x-12 gap-y-8 border-t border-white/5 pt-16">
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Chicken Seekh Kebab</span><span class="text-fiery-gold">$14</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Beef Seekh Kebab</span><span class="text-fiery-gold">$16</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Mutton Seekh Kebab</span><span class="text-fiery-gold">$18</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Chicken Boti Kebab</span><span class="text-fiery-gold">$15</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Beef Boti Kebab</span><span class="text-fiery-gold">$17</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Malai Chicken Kebab</span><span class="text-fiery-gold">$15</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Reshmi Kebab</span><span class="text-fiery-gold">$16</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Shami Kebab</span><span class="text-fiery-gold">$12</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Chapli Kebab</span><span class="text-fiery-gold">$14</span></div>
            </div>
        </div>

        <h3 class="text-2xl font-serif text-fiery-gold mt-24 mb-10 tracking-[0.2em] border-l-4 border-fiery-gold pl-4">International & Regional Fusion</h3>
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-x-12 gap-y-8">
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Doner Kebab</span><span class="text-fiery-gold">$13</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Turkish Adana Kebab</span><span class="text-fiery-gold">$19</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Shish Taouk Kebab</span><span class="text-fiery-gold">$15</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Tandoori Chicken Kebab</span><span class="text-fiery-gold">$16</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Hariyali Chicken Kebab</span><span class="text-fiery-gold">$15</span></div>
            </div>
            <div class="group border-b border-white/5 pb-4 hover:border-fiery-gold/50 transition">
                <div class="flex justify-between font-bold text-sm uppercase"><span>Afghani Chicken Kebab</span><span class="text-fiery-gold">$17</span></div>
            </div>
        </div>
    </section>

    <section id="order" class="py-24 bg-black border-y border-white/5 text-center">
        <div class="max-w-xl mx-auto px-6">
            <h2 class="text-4xl font-serif mb-6 italic">Taste the Smoke</h2>
            <p class="text-gray-500 mb-10 uppercase tracking-[0.2em] text-[10px]">Your Order Includes Instant Automated Invoicing</p>
            <a href="https://khan-kitchen-culinary.square.site" target="_blank" class="gold-button inline-block px-16 py-5 text-sm font-bold">
                Order Online
            </a>
        </div>
    </section>

    <footer class="py-12 text-center opacity-40 text-[10px] tracking-[0.5em] uppercase">
        <img src="logo.png" alt="Logo" class="h-8 mx-auto mb-4 grayscale">
        &copy; 2026 Khan Kitchen & Culinary
    </footer>

</body>
</html>
