<script lang="ts">
  import Button from './Button.svelte';
  
  let isMenuOpen = false;
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-cream/90 backdrop-blur-sm border-b border-gray-200/50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-20">
      <!-- Logo -->
      <div class="flex-shrink-0 flex items-center">
        <a href="/" class="flex items-center gap-2">
          <!-- Passionfroot Logo Icon -->
          <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M16 32C24.8366 32 32 24.8366 32 16C32 7.16344 24.8366 0 16 0C7.16344 0 0 7.16344 0 16C0 24.8366 7.16344 32 16 32Z" fill="#191817"/>
            <path d="M16 26C21.5228 26 26 21.5228 26 16C26 10.4772 21.5228 6 16 6C10.4772 6 6 10.4772 6 16C6 21.5228 10.4772 26 16 26Z" fill="#FF5D2A"/>
            <path d="M19.5 13.5L12.5 18.5" stroke="white" stroke-width="2" stroke-linecap="round"/>
            <path d="M12.5 13.5L19.5 18.5" stroke="white" stroke-width="2" stroke-linecap="round"/>
          </svg>
          <span class="font-bold text-xl tracking-tight">passionfroot</span>
        </a>
      </div>

      <!-- Desktop Navigation -->
      <div class="hidden md:flex items-center space-x-8">
        <div class="relative group">
          <button class="flex items-center gap-1 text-sm font-medium hover:text-orange-brand transition-colors">
            For Brands
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
          </button>
        </div>
        <div class="relative group">
          <button class="flex items-center gap-1 text-sm font-medium hover:text-orange-brand transition-colors">
            For Creators
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
          </button>
        </div>
      </div>

      <!-- Right Side -->
      <div class="hidden md:flex items-center space-x-6">
        <a href="#" class="text-sm font-medium hover:text-orange-brand transition-colors">About</a>
        <a href="#" class="text-sm font-medium hover:text-orange-brand transition-colors">Careers</a>
        <a href="#" class="text-sm font-medium hover:text-orange-brand transition-colors">Login</a>
        <Button href="#" className="!py-2 !px-4 !text-sm">Get access &rarr;</Button>
      </div>

      <!-- Mobile menu button -->
      <div class="md:hidden flex items-center">
        <button on:click={() => isMenuOpen = !isMenuOpen} class="text-gray-600 hover:text-gray-900 focus:outline-none">
          <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
          </svg>
        </button>
      </div>
    </div>
  </div>
</nav>
