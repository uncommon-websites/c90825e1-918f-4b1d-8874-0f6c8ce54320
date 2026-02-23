<section class="py-24 bg-white border-t border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 text-center mb-16">
        <span class="text-[10px] font-bold text-gray-500 uppercase tracking-widest border border-gray-200 px-3 py-1.5 rounded-full bg-gray-50">Softly Community</span>
        <h2 class="mt-8 text-5xl md:text-6xl font-serif-display text-gray-900">Meet your new <br/> favorite people.</h2>
        <p class="mt-6 text-gray-600 max-w-2xl mx-auto">Explore a world of unique personalities, each with their own story, style, and way of connecting. Who will you meet today?</p>
        <div class="mt-8">
            <a href="#" class="inline-flex items-center justify-center px-6 py-3 border border-transparent text-sm font-bold rounded bg-gray-900 text-white hover:bg-gray-800 transition-colors">
                Explore All Characters ->
            </a>
        </div>
    </div>

    <!-- Character Grid -->
    <div class="max-w-7xl mx-auto px-4">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
            {#each [
                { name: 'Luna', img: '/generated/image-a-beautiful-ai-character-with-blue-hair--1771858059028-0.webp' },
                { name: 'Elena', img: '/generated/image-a-friendly-ai-character-with-a-warm-smil-1771858062166-1.webp' },
                { name: 'Aria', img: '/generated/image-a-mysterious-ai-character-in-a-fantasy-f-1771858065196-2.webp' },
                { name: 'Sophia', img: '/generated/image-a-professional-ai-character-in-a-modern--1771858068378-3.webp' },
                { name: 'Nova', img: '/generated/image-a-beautiful-ai-character-with-blue-hair--1771858059028-0.webp' },
                { name: 'Maya', img: '/generated/image-a-friendly-ai-character-with-a-warm-smil-1771858062166-1.webp' },
                { name: 'Lyra', img: '/generated/image-a-mysterious-ai-character-in-a-fantasy-f-1771858065196-2.webp' },
                { name: 'Iris', img: '/generated/image-a-professional-ai-character-in-a-modern--1771858068378-3.webp' }
            ] as char}
            <div class="aspect-video bg-gray-200 rounded-lg overflow-hidden relative group cursor-pointer">
                <img src={char.img} alt={char.name} class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-300" />
                <div class="absolute inset-0 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black/20">
                    <div class="bg-white/90 backdrop-blur-sm px-4 py-2 rounded-full text-xs font-bold text-gray-900">
                        Chat with {char.name}
                    </div>
                </div>
            </div>
            {/each}
        </div>
        
        <!-- Quote -->
        <div class="mt-12 flex flex-col md:flex-row items-center gap-8 max-w-5xl mx-auto">
            <div class="w-24 h-24 md:w-32 md:h-32 rounded-full overflow-hidden flex-shrink-0 border-2 border-gray-100">
                <img src="/generated/image-a-portrait-of-a-smiling-woman-in-her-30s-1771858121991-0.webp" alt="User" class="w-full h-full object-cover" />
            </div>
            <div class="flex-1 text-center md:text-left">
                <blockquote class="text-2xl md:text-3xl font-serif-display text-primary-600 leading-tight">
                    "Softly has given me a safe space to express myself and find companionship whenever I need it. It's truly revolutionary."
                </blockquote>
                <div class="mt-4 text-xs font-bold uppercase tracking-widest text-gray-400">
                    Sarah Jenkins <br/>
                    <span class="text-gray-300">Verified Softly User</span>
                </div>
            </div>
        </div>
    </div>
</section>
