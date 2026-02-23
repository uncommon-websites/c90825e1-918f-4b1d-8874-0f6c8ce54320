<script>
    // Hero Component
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 bg-gray-50 relative overflow-hidden font-sans">
    <!-- Grid Background Pattern -->
    <div class="absolute inset-0 z-0 opacity-[0.4]" 
         style="background-image: linear-gradient(#e5e7eb 1px, transparent 1px), linear-gradient(90deg, #e5e7eb 1px, transparent 1px); background-size: 40px 40px;">
    </div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 flex flex-col items-center text-center">
        
        <!-- Headline -->
        <h1 class="text-5xl md:text-7xl lg:text-8xl font-serif-display text-gray-900 leading-[1.1] tracking-tight mb-6 max-w-5xl mx-auto">
            Find your <br class="hidden md:block" />
            perfect 
            <span class="inline-flex items-center align-middle mx-1 md:mx-2 relative -top-1 md:-top-2">
                <svg width="60" height="60" viewBox="0 0 100 100" class="w-10 h-10 md:w-16 md:h-16 text-primary-500 animate-spin-slow" fill="currentColor">
                    <!-- Stylized Asterisk/Flower -->
                    <path d="M50 0 L60 35 L95 25 L70 50 L95 75 L60 65 L50 100 L40 65 L5 75 L30 50 L5 25 L40 35 Z" />
                </svg>
            </span>
            companion
        </h1>

        <!-- Subheadline -->
        <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
            Softly brings AI-powered virtual companionship to life. Experience personalized, immersive digital relationships that evolve with you.
        </p>

        <!-- CTA -->
        <div class="mb-16">
            <a href="#" class="inline-flex items-center justify-center px-8 py-4 border border-transparent text-base font-medium rounded-full text-white bg-brand-primary hover:bg-brand-primary-hover transition-all shadow-lg hover:shadow-xl transform hover:-translate-y-0.5">
                Start Your Journey
                <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
            </a>
        </div>

        <!-- Hero Image -->
        <div class="w-full max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl bg-black aspect-video relative group cursor-pointer">
            <img 
                src="/generated/image-a-beautiful-ethereal-digital-companion-c-1771857432256-0.webp" 
                alt="Softly AI Companion" 
                class="w-full h-full object-cover opacity-90 group-hover:opacity-100 transition-opacity duration-500"
            />
            
            <!-- Overlay Content -->
            <div class="absolute inset-0 flex flex-col items-center justify-center text-center p-8 bg-black/20 group-hover:bg-black/10 transition-all">
                <!-- Play Button Circle -->
                <div class="w-16 h-16 md:w-20 md:h-20 bg-white/20 backdrop-blur-sm rounded-full flex items-center justify-center mb-6 group-hover:bg-white/30 transition-all border border-white/30">
                    <svg class="w-8 h-8 md:w-10 md:h-10 text-white fill-current ml-1" viewBox="0 0 24 24">
                        <path d="M8 5v14l11-7z" />
                    </svg>
                </div>

                <h3 class="text-white text-xl md:text-2xl font-medium mb-2 drop-shadow-lg">Meet your new best friend.</h3>
                <p class="text-white/80 text-sm md:text-base max-w-lg drop-shadow-md">
                    Watch how Softly creates deeply personal and meaningful connections.
                </p>
            </div>
            
            <!-- Progress Bar -->
            <div class="absolute bottom-0 left-0 right-0 h-1.5 bg-white/20">
                <div class="h-full w-2/3 bg-brand-primary"></div>
            </div>
        </div>
    </div>
</section>
