<script>
  import { onMount } from 'svelte';
  
  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 0;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<div class="fixed top-0 w-full z-50 flex flex-col font-sans">
  <!-- Top Banner -->
  <div class="bg-primary-50 border-b border-primary-100 py-2 px-4 text-center text-[10px] sm:text-xs font-medium tracking-wide text-primary-900">
    <span class="mr-1">Experience the future of digital companionship. Softly 2.0 is now live!</span>
    <a href="#" class="inline-flex items-center hover:underline font-bold ml-1">
      EXPLORE NOW 
      <svg class="w-3 h-3 ml-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
    </a>
  </div>

  <!-- Main Nav -->
  <nav class="bg-white/95 backdrop-blur-sm border-b border-gray-100 transition-all duration-200 {isScrolled ? 'py-3' : 'py-4'}">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between">
      <!-- Logo -->
      <div class="flex items-center">
        <a href="/" class="flex items-center">
          <svg width="80" height="54" viewBox="0 0 117 78" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M83.0101 48.3334H67.6809C65.1171 48.3334 62.6584 49.3518 60.8454 51.1647L56.8415 55.1687C55.0285 56.9817 52.5698 58 50.0059 58H34.6768C26.6686 58 20.1768 51.5081 20.1768 43.5C20.1768 35.4919 26.6686 29 34.6768 29H50.0059C52.5698 29 55.0285 27.9817 56.8415 26.1687L60.8454 22.1647C62.6584 20.3518 65.1171 19.3334 67.6809 19.3334H83.0101C91.0182 19.3334 97.5101 25.8253 97.5101 33.8334C97.5101 41.8415 91.0182 48.3334 83.0101 48.3334ZM67.6809 29C65.1171 29 62.6584 30.0184 60.8454 31.8314L56.8415 35.8353C55.0285 37.6483 52.5698 38.6667 50.0059 38.6667H34.6768C32.0073 38.6667 29.8434 40.8306 29.8434 43.5C29.8434 46.1695 32.0073 48.3334 34.6768 48.3334H50.0059C52.5698 48.3334 55.0285 47.315 56.8415 45.502L60.8454 41.4981C62.6584 39.6851 65.1171 38.6667 67.6809 38.6667H83.0101C85.6795 38.6667 87.8434 36.5028 87.8434 33.8334C87.8434 31.1639 85.6795 29 83.0101 29H67.6809Z" fill="black"/>
            <path fill-rule="evenodd" clip-rule="evenodd" d="M83.0104 67.6667H67.6813C65.1174 67.6667 62.6587 68.6851 60.8457 70.498L56.8418 74.502C55.0288 76.3149 52.5701 77.3333 50.0062 77.3333H34.6771C15.9914 77.3333 0.84375 62.1857 0.84375 43.5C0.84375 24.8143 15.9914 9.66667 34.6771 9.66667H50.0062C52.5701 9.66667 55.0288 8.64828 56.8418 6.8353L60.8457 2.83129C62.6587 1.01846 65.1174 0 67.6813 0H83.0104C101.696 0 116.844 15.1477 116.844 33.8333C116.844 52.519 101.696 67.6667 83.0104 67.6667ZM67.6813 9.66667C65.1174 9.66667 62.6587 10.6851 60.8457 12.498L56.8418 16.502C55.0288 18.3149 52.5701 19.3333 50.0062 19.3333H34.6771C21.3302 19.3333 10.5104 30.1532 10.5104 43.5C10.5104 56.8468 21.3302 67.6667 34.6771 67.6667H50.0062C52.5701 67.6667 55.0288 66.6483 56.8418 64.8353L60.8457 60.8314C62.6587 59.0184 65.1174 58 67.6813 58H83.0104C96.3572 58 107.177 47.1801 107.177 33.8333C107.177 20.4866 96.3572 9.66667 83.0104 9.66667H67.6813Z" fill="black"/>
          </svg>
        </a>
        
        <!-- Desktop Links -->
        <div class="hidden md:flex items-center ml-10 space-x-8 text-sm font-medium text-gray-600">
          <a href="#" class="hover:text-gray-900">Characters</a>
          <a href="#" class="hover:text-gray-900">Features</a>
          <a href="#" class="hover:text-gray-900">Community</a>
          <a href="#" class="hover:text-gray-900">Pricing</a>
        </div>
      </div>

      <!-- Right Actions -->
      <div class="flex items-center space-x-4 sm:space-x-6">
        <a href="#" class="hidden md:block text-sm font-medium text-gray-600 hover:text-gray-900">Log In</a>
        <a href="#" class="inline-flex items-center justify-center px-4 py-2 border border-transparent text-sm font-medium rounded-full text-white bg-brand-primary hover:bg-brand-primary-hover transition-colors shadow-sm">
          Get Started
          <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </a>
      </div>
    </div>
  </nav>
</div>
