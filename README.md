
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khan Kitchen & Culinary | Premium Dining</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --gold: #D4AF37;
            --smoke: rgba(255, 255, 255, 0.1);
        }
        body { font-family: 'Inter', sans-serif; background-color: #050505; color: white; scroll-behavior: smooth; }
        .font-serif { font-family: 'Cinzel', serif; }
        
        /* Gold Hover Effect */
        .gold-button {
            border: 1px solid var(--gold);
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }
        .gold-button:hover {
            background-color: var(--gold);
            color: black;
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.4);
        }

        /* Smoke Animation Overlay */
        .smoke-overlay {
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            background: url('https://www.transparenttextures.com/patterns/asfalt-dark.png');
            opacity: 0.3;
            pointer-events: none;
        }

        /* Parallax Background */
        .parallax {
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }

        /* Logo Glow */
        .logo-glow {
            text-shadow: 0 0 15px rgba(212, 175, 55, 0.6);
        }
    </style>
</head>
<body>

    <header id="home" class="relative h-screen w-full flex items-center justify-center overflow-hidden">
        <video autoplay muted loop playsinline class="absolute z-0 w-auto min-w-full min-h-full max-w-none">
            <source src="https://assets.mixkit.co/videos/preview/mixkit-grilling-meat-and-vegetables-on-a-flaming-grill-4235-large.mp4" type="video/mp4">
        </video>
        
        <div class="absolute z-10 w-full h-full bg-gradient-to-b from-black/60 via-black/40 to-[#050505]"></div>
        <div class="smoke-overlay z-20"></div>

        <div class="relative z-30 text-center px-4">
            <div class="mb-4">
                <span class="block text-gold text-sm tracking-[0.5em] uppercase mb-2">Established 2026</span>
                <h1 class="text-5xl md:text-8xl font-serif font-bold text-[#D4AF37] logo-glow tracking-tighter">KHAN</h1>
                <p class="text-xl md:text-2xl font-serif text-white tracking-[0.3em] mt-2">KITCHEN & CULINARY</p>
            </div>
            <div class="mt-10">
                <a href="#order" class="gold-button px-10 py-4 text-sm font-semibold uppercase tracking-widest">Order Now</a>
            </div>
        </div>
    </header>

    <section id="menu" class="py-24 bg-[#050505] relative overflow-hidden">
        <div class="max-w-6xl mx-auto px-6 relative z-10">
            <div class="flex flex-col md:flex-row justify-between items-end mb-16 border-b border-white/10 pb-8">
                <div>
                    <h2 class="text-4xl font-serif text-[#D4AF37]">Our Signature Kebabs 🍢</h2>
                    <p class="text-gray-400 mt-2">Smoked over natural charcoal</p>
                </div>
            </div>

            <div class="grid md:grid-cols-2 gap-16">
                <div class="flex justify-between items-center group cursor-pointer">
                    <div class="border-l-2 border-[#D4AF37] pl-6 transition-all group-hover:pl-8">
                        <h4 class="text-xl font-semibold">Reshmi Malai Kebab</h4>
                        <p class="text-gray-500 text-sm mt-1 italic">Silky cream-marinated chicken</p>
                    </div>
                    <span class="text-[#D4AF37] font-bold">$18</span>
                </div>
                <div class="flex justify-between items-center group cursor-pointer">
                    <div class="border-l-2 border-[#D4AF37] pl-6 transition-all group-hover:pl-8">
                        <h4 class="text-xl font-semibold">Mutton Seekh Kebab</h4>
                        <p class="text-gray-500 text-sm mt-1 italic">Traditional spice-blend skewers</p>
                    </div>
                    <span class="text-[#D4AF37] font-bold">$22</span>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 parallax" style="background-image: url('https://images.unsplash.com/photo-1529692236671-f1f6cf9683ba?auto=format&fit=crop&w=1920&q=80');">
        <div class="absolute inset-0 bg-black/80"></div>
        <div class="max-w-6xl mx-auto px-6 relative z-10 text-center">
            <h2 class="text-4xl font-serif text-[#D4AF37] mb-12">Chef Specials 🍛</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="p-8 bg-black/40 backdrop-blur-md border border-white/5 rounded-sm hover:border-gold/30 transition">
                    <h4 class="text-xl font-bold mb-2">Khan Shahi Biryani</h4>
                    <p class="text-gray-400 text-sm">Long-grain basmati with slow-cooked premium lamb.</p>
                </div>
                <div class="p-8 bg-black/40 backdrop-blur-md border border-white/5 rounded-sm hover:border-gold/30 transition">
                    <h4 class="text-xl font-bold mb-2">Butter Chicken Gold</h4>
                    <p class="text-gray-500 text-sm">Our signature recipe with a touch of smoked butter.</p>
                </div>
                <div class="p-8 bg-black/40 backdrop-blur-md border border-white/5 rounded-sm hover:border-gold/30 transition">
                    <h4 class="text-xl font-bold mb-2">Handi Mutton</h4>
                    <p class="text-gray-400 text-sm">Clay-pot slow-cooked curry with secret 21 spices.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="order" class="py-32 text-center bg-[#050505]">
        <div class="max-w-xl mx-auto px-6 border border-[#D4AF37]/20 py-16 bg-black">
            <i class="fas fa-file-invoice text-3xl text-gold mb-6 block"></i>
            <h3 class="text-2xl font-serif mb-4 tracking-wider">SECURE CHECKOUT</h3>
            <p class="text-gray-500 mb-10 text-sm leading-relaxed uppercase tracking-[0.2em]">Automated Invoicing & Instant Confirmation</p>
            
            <a href="https://khan-kitchen-culinary.square.site" class="gold-button inline-block px-16 py-5 text-sm font-bold tracking-[0.3em] uppercase">
                Order Online
            </a>
        </div>
    </section>

    <footer class="bg-black border-t border-white/5 py-20 px-6">
        <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-16 text-center md:text-left">
            <div>
                <h3 class="font-serif text-[#D4AF37] text-2xl mb-6">Location & Contact</h3>
                <p class="text-gray-400 leading-loose">123 Culinary Avenue, Food District<br>Dhaka, Bangladesh</p>
                <p class="text-white mt-4 font-semibold">+880 1XXX-XXXXXX</p>
            </div>
            <div class="md:text-right">
                <h3 class="font-serif text-[#D4AF37] text-2xl mb-6">Dining Hours</h3>
                <p class="text-gray-400 leading-loose">Mon - Thu: 12:00 PM - 10:00 PM<br>Fri - Sun: 11:00 AM - 11:00 PM</p>
            </div>
        </div>
        <div class="text-center mt-20 text-xs text-gray-700 tracking-[0.5em] uppercase">
            &copy; 2026 Khan Kitchen & Culinary
        </div>
    </footer>

</body>
</html>
