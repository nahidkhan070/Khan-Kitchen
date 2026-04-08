
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khan Kitchen & Culinary | Premium Dining Experience</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --fiery-gold: #FF9900; /* Matching the logo's spark */
            --logo-gold: #D4AF37; /* The primary gold */
            --dark-gold: #664411; /* For shadow/hover */
        }
        body { font-family: 'Inter', sans-serif; background-color: #050505; color: white; scroll-behavior: smooth; overflow-x: hidden; }
        .font-serif { font-family: 'Cinzel', serif; }
        
        /* Gold Button Styling */
        .gold-button {
            border: 1px solid var(--fiery-gold);
            color: var(--fiery-gold);
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }
        .gold-button:hover {
            background-color: var(--fiery-gold);
            color: black;
            box-shadow: 0 0 25px rgba(255, 153, 0, 0.5);
        }

        /* Smoke/Grain Overlay */
        .smoke-overlay {
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            background: url('https://www.transparenttextures.com/patterns/black-felt.png');
            opacity: 0.15;
            pointer-events: none;
            mix-blend-mode: overlay;
        }

        /* Hero Video Setup */
        .video-container {
            position: absolute;
            z-index: 0;
            width: 100%; height: 100%;
            overflow: hidden;
        }
        .video-container video {
            position: absolute;
            top: 50%; left: 50%;
            transform: translate(-50%, -50%);
            min-width: 100%; min-h-100%;
            object-fit: cover;
        }

        /* logo-main (Hero) glow effect */
        .hero-logo img {
            filter: drop-shadow(0 0 20px rgba(212, 175, 55, 0.4));
        }
    </style>
</head>
<body>

    <nav class="fixed top-0 left-0 w-full z-50 bg-[#050505]/90 backdrop-blur-md border-b border-white/5">
        <div class="max-w-7xl mx-auto px-6 py-2 flex justify-between items-center">
            <div class="flex items-center space-x-3 h-12">
                <img src="logo.png" alt="Khan Kitchen & Culinary" class="h-full object-contain">
            </div>
            <div class="hidden md:flex space-x-10 text-xs font-semibold uppercase tracking-widest text-gray-300">
                <a href="#home" class="hover:text-gold transition">Home</a>
                <a href="#menu" class="hover:text-gold transition">Menu</a>
                <a href="#location" class="hover:text-gold transition">Find Us</a>
                <a href="#order" class="text-fiery-gold font-bold">Order Online</a>
            </div>
        </div>
    </nav>

    <header id="home" class="relative h-screen w-full flex items-center justify-center text-center overflow-hidden">
        <div class="video-container">
            <video autoplay muted loop playsinline>
                <source src="https://assets.mixkit.co/videos/preview/mixkit-grilling-meat-and-vegetables-on-a-flaming-grill-4235-large.mp4" type="video/mp4">
            </video>
        </div>
        
        <div class="absolute z-10 w-full h-full bg-gradient-to-b from-black/80 via-black/60 to-[#050505]"></div>
        <div class="smoke-overlay z-20"></div>

        <div class="relative z-30 flex flex-col items-center justify-center px-6">
            <div class="hero-logo w-auto h-[40vh] md:h-[50vh] flex items-center justify-center mb-10">
                <img src="logo.png" alt="Khan Culinary Premium Logo" class="w-full h-full object-contain">
            </div>
            
            <div class="gold-hover mt-10">
                <a href="#order" class="gold-button inline-block px-14 py-4 text-xs font-bold tracking-[0.3em] uppercase">
                    Place Your Order
                </a>
            </div>
        </div>
    </header>

    <section id="menu" class="py-24 bg-[#050505] relative z-10">
        <div class="max-w-6xl mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-end mb-16 pb-6 border-b border-gold/10">
                <div>
                    <h2 class="text-4xl font-serif text-[#D4AF37]">Signature Kebabs 🍢</h2>
                    <p class="text-gray-500 mt-2 font-light italic">Fiery. Tender. Authentic.</p>
                </div>
            </div>

            <div class="grid md:grid-cols-2 gap-x-16 gap-y-12">
                <div class="flex justify-between items-center group cursor-pointer border-l border-gold/10 pl-6 hover:border-gold/30 transition">
                    <div>
                        <h4 class="text-xl font-semibold">Reshmi Malai Kebab</h4>
                        <p class="text-gray-600 text-sm mt-1">Chicken marinated in heavy cream and mild spices.</p>
                    </div>
                    <span class="text-gold font-bold">$18</span>
                </div>
                <div class="flex justify-between items-center group cursor-pointer border-l border-gold/10 pl-6 hover:border-gold/30 transition">
                    <div>
                        <h4 class="text-xl font-semibold">Khan Seekh Kebab (Mutton)</h4>
                        <p class="text-gray-600 text-sm mt-1">Our signature spice blend, charcoal grilled.</p>
                    </div>
                    <span class="text-gold font-bold">$22</span>
                </div>
                <div class="flex justify-between items-center group cursor-pointer border-l border-gold/10 pl-6 hover:border-gold/30 transition">
                    <div>
                        <h4 class="text-xl font-semibold">Bihari Boti Kebab</h4>
                        <p class="text-gray-600 text-sm mt-1">Traditional beef strips with smoked chili aroma.</p>
                    </div>
                    <span class="text-gold font-bold">$16</span>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 relative parallax" style="background-image: url('https://images.unsplash.com/photo-1514326640560-7d063ef2aed5?auto=format&fit=crop&w=1920&q=80'); background-attachment: fixed; background-size: cover; background-position: center;">
        <div class="absolute inset-0 bg-black/80 z-0"></div>
        <div class="max-w-6xl mx-auto px-6 relative z-10 text-center">
            <h2 class="text-4xl font-serif text-[#D4AF37] mb-12">Chef Specials 🍛</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="p-8 bg-black/40 backdrop-blur-md border border-white/5 rounded-sm">
                    <h4 class="text-xl font-bold mb-2">Khan Shahi Biryani</h4>
                    <p class="text-gray-500 text-sm">Long-grain basmati with slow-cooked premium lamb.</p>
                </div>
                <div class="p-8 bg-black/40 backdrop-blur-md border border-fiery-gold/10 rounded-sm">
                    <h4 class="text-xl font-bold mb-2">Butter Chicken Gold</h4>
                    <p class="text-gray-400 text-sm">Our signature recipe with a touch of smoked butter.</p>
                </div>
                <div class="p-8 bg-black/40 backdrop-blur-md border border-white/5 rounded-sm">
                    <h4 class="text-xl font-bold mb-2">Clay Pot Handi Mutton</h4>
                    <p class="text-gray-500 text-sm">Pot slow-cooked curry with 21 secret spices.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="location" class="py-24 bg-[#050505]">
        <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-16 px-6 text-center md:text-left">
            <div>
                <h3 class="font-serif text-[#D4AF37] text-2xl mb-6">Location & Contact
