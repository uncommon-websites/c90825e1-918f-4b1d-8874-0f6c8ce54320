<script>
    const publications = [
        { name: 'TechCrunch', domain: 'techcrunch.com' },
        { name: 'Wired', domain: 'wired.com' },
        { name: 'The Verge', domain: 'theverge.com' },
        { name: 'Mashable', domain: 'mashable.com' },
        { name: 'Forbes', domain: 'forbes.com' }
    ];
</script>

<section class="py-12 bg-white border-b border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="text-center text-[10px] uppercase tracking-widest text-primary-600 font-bold mb-8">
            AS FEATURED IN
        </p>

        <div class="flex flex-wrap justify-center items-center gap-8 md:gap-16 opacity-50 grayscale hover:grayscale-0 transition-all duration-500">
            {#each publications as pub}
                <div class="flex items-center justify-center h-8">
                    <span class="text-xl md:text-2xl font-bold text-gray-900">{pub.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
