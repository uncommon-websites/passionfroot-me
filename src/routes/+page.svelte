<script lang="ts">
  import Navbar from '$lib/Navbar.svelte';
  import Footer from '$lib/Footer.svelte';
  import Button from '$lib/Button.svelte';
</script>

<div class="min-h-screen font-sans text-dark bg-cream overflow-x-hidden">
  <Navbar />

  <!-- Hero Section -->
  <section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto text-center">
    <div class="mb-6">
      <span class="text-xs font-bold tracking-widest text-gray-500 uppercase">The #1 Creator Marketing Platform</span>
    </div>
    <h1 class="text-5xl md:text-7xl font-serif mb-6 leading-tight">
      Where B2B brands scale <br class="hidden md:block" /> influencer marketing
    </h1>
    <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
      The fastest and easiest way to do influencer marketing at scale.
      Find the right creators on all platforms, book, collaborate, and pay – all in one place.
    </p>
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
      <Button href="#" type="primary">Get access &rarr;</Button>
      <Button href="#" type="outline">Talk to us</Button>
    </div>

    <!-- Hero Image Placeholder -->
    <div class="relative w-full max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-gray-200 bg-white aspect-[16/9] mb-16 group">
      <!-- Mock UI -->
      <div class="absolute inset-0 bg-gray-50 p-4">
        <div class="h-full w-full bg-white rounded-xl border border-gray-200 shadow-sm p-6 flex flex-col">
            <!-- Header of Mock UI -->
            <div class="flex items-center justify-between mb-6 border-b border-gray-100 pb-4">
                <div class="flex items-center gap-3">
                    <div class="w-8 h-8 rounded-full bg-orange-100"></div>
                    <div class="h-4 w-32 bg-gray-100 rounded"></div>
                </div>
                <div class="flex gap-2">
                    <div class="h-8 w-20 bg-gray-100 rounded"></div>
                    <div class="h-8 w-20 bg-gray-100 rounded"></div>
                </div>
            </div>
            <!-- Content of Mock UI -->
            <div class="flex-1 grid grid-cols-12 gap-6">
                <div class="col-span-3 space-y-3">
                    <div class="h-4 w-full bg-gray-100 rounded"></div>
                    <div class="h-4 w-3/4 bg-gray-100 rounded"></div>
                    <div class="h-4 w-5/6 bg-gray-100 rounded"></div>
                </div>
                <div class="col-span-9 bg-gray-50 rounded-lg p-4 grid grid-cols-2 gap-4">
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                </div>
            </div>
        </div>
      </div>
      
      <!-- Decorative Elements -->
      <div class="absolute -left-12 bottom-12 w-24 h-24 bg-orange-brand rounded-full blur-2xl opacity-20"></div>
      <div class="absolute -right-12 top-12 w-32 h-32 bg-purple-400 rounded-full blur-2xl opacity-20"></div>

      <!-- Cartoon Character (Orange Blob) -->
      <div class="absolute bottom-[-20px] left-[-40px] w-32 h-32 z-10 hidden md:block">
          <svg viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M50 90C75 90 90 70 90 50C90 30 70 10 50 10C30 10 10 30 10 50C10 70 25 90 50 90Z" fill="#FF5D2A"/>
            <circle cx="35" cy="40" r="5" fill="white"/>
            <circle cx="65" cy="40" r="5" fill="white"/>
            <path d="M35 60 Q50 70 65 60" stroke="white" stroke-width="3" stroke-linecap="round"/>
            <!-- Arms -->
            <path d="M10 50 Q-5 30 15 20" stroke="#FF5D2A" stroke-width="8" stroke-linecap="round"/>
          </svg>
      </div>
    </div>

    <!-- Logos -->
    <div class="text-center">
      <p class="text-sm text-gray-500 mb-6">Powering thousands of marketing teams at the fastest growing companies in tech</p>
      <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12 opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
        <!-- Linktree -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-green-600 rounded-full"></div> Linktree</span>
        <!-- Raycast -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-red-500 rounded"></div> Raycast</span>
        <!-- Gamma -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-yellow-500 rounded-tr-xl"></div> Gamma</span>
        <!-- Superhuman -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-purple-600 rounded-full"></div> Superhuman</span>
        <!-- Framer -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-black rounded-tl-xl"></div> Framer</span>
        <!-- Rippling -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-yellow-400 rounded-full"></div> Rippling</span>
      </div>
    </div>
  </section>

  <!-- Stats Section -->
  <section class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-3xl mx-auto">
        Get direct access to the top B2B creators in the world - on all platforms
      </h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">300 Million</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Target Audience</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">2 Billion</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Monthly Impressions</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">60%</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Lower CPC than LinkedIn Ads*</div>
        </div>
      </div>

      <!-- Creator Cards Carousel Mockup -->
      <div class="flex gap-4 overflow-hidden relative">
        <div class="absolute inset-y-0 left-0 w-20 bg-gradient-to-r from-white to-transparent z-10"></div>
        <div class="absolute inset-y-0 right-0 w-20 bg-gradient-to-l from-white to-transparent z-10"></div>
        
        <div class="flex gap-4 animate-scroll">
            <!-- Card 1 -->
            <div class="w-64 h-80 bg-pink-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-pink-500 rounded-full"></div> TikTok
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Tech Daily</div>
                    <div class="text-xs opacity-80">500k Followers</div>
                </div>
            </div>
            <!-- Card 2 -->
            <div class="w-64 h-80 bg-orange-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-orange-500 rounded-full"></div> Newsletter
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">The Hustle</div>
                    <div class="text-xs opacity-80">2M Subscribers</div>
                </div>
            </div>
            <!-- Card 3 -->
            <div class="w-64 h-80 bg-red-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-red-500 rounded-full"></div> YouTube
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">MKBHD</div>
                    <div class="text-xs opacity-80">18M Subscribers</div>
                </div>
            </div>
             <!-- Card 4 -->
            <div class="w-64 h-80 bg-blue-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-blue-500 rounded-full"></div> LinkedIn
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Sahil Bloom</div>
                    <div class="text-xs opacity-80">1M Followers</div>
                </div>
            </div>
             <!-- Card 5 -->
            <div class="w-64 h-80 bg-purple-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-2 py-1 rounded-full text-xs font-bold flex items-center gap-1">
                    <div class="w-2 h-2 bg-purple-500 rounded-full"></div> Podcast
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">My First Million</div>
                    <div class="text-xs opacity-80">100k Downloads</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Disrupted Section -->
  <section class="bg-dark text-white py-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">Traditional marketing is <br /> being disrupted</h2>
      <p class="text-center text-gray-400 mb-16">We're entering a new era of personality-led growth.</p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <!-- The Old Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">The Old Way</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Marketers try to build their brand through paid search, outbound, and SEO - but the channels have become crowded and expensive.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 relative">
             <div class="flex justify-between items-end h-40 gap-2">
                <div class="w-full bg-red-500/20 rounded-t h-[40%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-red-400">$20</div></div>
                <div class="w-full bg-red-500/40 rounded-t h-[60%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-red-400">$45</div></div>
                <div class="w-full bg-red-500/60 rounded-t h-[80%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-red-400">$80</div></div>
                <div class="w-full bg-red-500/80 rounded-t h-[90%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-red-400">$120</div></div>
                <div class="w-full bg-red-500 rounded-t h-full relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-red-400 font-bold">$150</div></div>
             </div>
             <div class="mt-4 flex justify-between text-xs text-gray-500">
                <span>2014</span>
                <span>2024</span>
             </div>
             <div class="absolute top-4 left-4 text-xs font-bold text-gray-300">CAC (Customer Acquisition Cost)</div>
          </div>
        </div>

        <!-- The New Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">The New Way</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Hyper-scale your brand and top-of-funnel growth through trusted creator audiences. Cut through the noise and build quality inbound.
          </p>
          <div class="relative h-64 flex items-center justify-center">
             <!-- Central Character -->
             <div class="relative z-10 w-24 h-24">
                <svg viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M50 90C75 90 90 70 90 50C90 30 70 10 50 10C30 10 10 30 10 50C10 70 25 90 50 90Z" fill="#FF5D2A"/>
                    <circle cx="35" cy="40" r="5" fill="white"/>
                    <circle cx="65" cy="40" r="5" fill="white"/>
                    <path d="M35 60 Q50 70 65 60" stroke="white" stroke-width="3" stroke-linecap="round"/>
                </svg>
             </div>
             <!-- Orbiting Icons -->
             <div class="absolute inset-0 animate-spin-slow">
                <div class="absolute top-0 left-1/2 -translate-x-1/2 -translate-y-4 w-10 h-10 bg-blue-500 rounded-full flex items-center justify-center text-white text-xs">Li</div>
                <div class="absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-4 w-10 h-10 bg-pink-500 rounded-full flex items-center justify-center text-white text-xs">Ig</div>
                <div class="absolute left-0 top-1/2 -translate-x-4 -translate-y-1/2 w-10 h-10 bg-red-500 rounded-full flex items-center justify-center text-white text-xs">Yt</div>
                <div class="absolute right-0 top-1/2 translate-x-4 -translate-y-1/2 w-10 h-10 bg-black rounded-full flex items-center justify-center text-white text-xs">X</div>
             </div>
             <!-- Megaphone Effect -->
             <div class="absolute right-0 top-1/2 -translate-y-1/2 translate-x-20 opacity-50">
                <svg width="100" height="100" viewBox="0 0 100 100" fill="none">
                    <path d="M0 50 L100 20" stroke="#FF5D2A" stroke-width="2" stroke-dasharray="4 4"/>
                    <path d="M0 50 L100 50" stroke="#FF5D2A" stroke-width="2" stroke-dasharray="4 4"/>
                    <path d="M0 50 L100 80" stroke="#FF5D2A" stroke-width="2" stroke-dasharray="4 4"/>
                </svg>
             </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section 1 (Purple) -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Find the best creators for your brand - fast.
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1: AI Search -->
        <div class="lg:col-span-2 bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden relative group">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">AI-powered creator search</h3>
                <p class="text-gray-500 text-sm">Our AI lets you search all platforms - not just one. Simply search and find the right creator ambassadors for your business in minutes.</p>
            </div>
            <div class="bg-purple-50 rounded-xl p-6 h-64 relative border border-purple-100">
                <!-- Mock Search Bar -->
                <div class="bg-white rounded-full p-2 shadow-sm flex items-center gap-2 mb-4 w-3/4 mx-auto">
                    <div class="w-8 h-8 bg-purple-100 rounded-full flex items-center justify-center text-purple-600">✨</div>
                    <div class="text-sm text-gray-400">Tech & Startups</div>
                    <div class="ml-auto bg-black text-white px-4 py-1.5 rounded-full text-xs font-bold">Search</div>
                </div>
                <!-- Results Mockup -->
                <div class="flex gap-4 justify-center">
                    <div class="bg-white p-3 rounded-xl shadow-sm w-32">
                        <div class="w-8 h-8 bg-gray-200 rounded-full mb-2"></div>
                        <div class="h-2 w-16 bg-gray-100 rounded mb-1"></div>
                        <div class="h-2 w-10 bg-gray-100 rounded"></div>
                    </div>
                    <div class="bg-white p-3 rounded-xl shadow-sm w-32">
                        <div class="w-8 h-8 bg-gray-200 rounded-full mb-2"></div>
                        <div class="h-2 w-16 bg-gray-100 rounded mb-1"></div>
                        <div class="h-2 w-10 bg-gray-100 rounded"></div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Card 2: Network -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">World's largest B2B creator network</h3>
                <p class="text-gray-500 text-sm">The largest selection of creators across Newsletters, LinkedIn, YouTube, Instagram, Twitter, and more.</p>
            </div>
            <div class="bg-purple-50 rounded-xl h-48 relative overflow-hidden flex items-center justify-center">
                <div class="absolute inset-0 bg-[url('https://upload.wikimedia.org/wikipedia/commons/e/ec/World_map_blank_without_borders.svg')] bg-contain bg-no-repeat bg-center opacity-10"></div>
                <div class="flex gap-2 flex-wrap justify-center p-4">
                    <span class="bg-white px-2 py-1 rounded shadow-sm text-xs">Newsletter</span>
                    <span class="bg-white px-2 py-1 rounded shadow-sm text-xs">YouTube</span>
                    <span class="bg-white px-2 py-1 rounded shadow-sm text-xs">LinkedIn</span>
                </div>
            </div>
        </div>

        <!-- Card 3: Media Kits -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 relative">
                <div class="bg-white rounded-xl shadow-sm p-4 h-full w-full relative transform rotate-[-2deg]">
                    <div class="flex items-center gap-3 mb-3">
                        <div class="w-10 h-10 bg-gray-200 rounded-full"></div>
                        <div>
                            <div class="h-3 w-20 bg-gray-100 rounded mb-1"></div>
                            <div class="h-2 w-12 bg-gray-100 rounded"></div>
                        </div>
                    </div>
                    <div class="flex gap-2 mt-4">
                        <div class="h-16 w-1/3 bg-purple-100 rounded-lg"></div>
                        <div class="h-16 w-1/3 bg-orange-100 rounded-lg"></div>
                        <div class="h-16 w-1/3 bg-blue-100 rounded-lg"></div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Creator media kits</h3>
             <p class="text-gray-500 text-sm">Analyze creators with verified stats, past prices, rates, and much more.</p>
        </div>

        <!-- Card 4: Recommendations -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 flex items-center justify-center">
                <div class="bg-white p-4 rounded-xl shadow-sm w-full max-w-[200px]">
                    <div class="text-xs text-gray-400 mb-2">We need to reach our new AI video tool to growth experts...</div>
                    <div class="flex justify-end">
                        <div class="bg-black text-white text-xs px-3 py-1.5 rounded-lg">2.1k/M</div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">AI creator recommendations</h3>
             <p class="text-gray-500 text-sm">Tell us your goals - and our AI will build a campaign for you in seconds.</p>
        </div>

        <!-- Card 5: Evaluate -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 flex items-center justify-center relative">
                 <div class="bg-white p-4 rounded-xl shadow-sm w-full max-w-[220px] flex items-center gap-4">
                    <div class="w-12 h-12 rounded-full bg-gray-200"></div>
                    <div class="flex-1">
                        <div class="h-3 w-20 bg-gray-100 rounded mb-2"></div>
                        <div class="h-2 w-full bg-gray-50 rounded"></div>
                    </div>
                    <div class="w-10 h-10 rounded-full border-4 border-green-400 flex items-center justify-center text-xs font-bold text-green-600">98</div>
                 </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Evaluate a creator in seconds</h3>
             <p class="text-gray-500 text-sm">Our AI evaluates and summarizes their latest content - no more digging in their feeds.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial 1 -->
  <section class="py-16 bg-cream">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="flex justify-center mb-8">
            <div class="flex items-center gap-2 font-bold text-xl opacity-80">
                <div class="w-6 h-6 bg-black rounded"></div> INTERCOM
            </div>
        </div>
        <blockquote class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
            "Partnering with creators through Passionfroot has been a game-changer for Intercom's Startup program. By collaborating with top newsletters, we've reached thousands of founders."
        </blockquote>
        <div class="flex items-center justify-center gap-4">
            <div class="w-12 h-12 rounded-full bg-gray-300"></div>
            <div class="text-left">
                <div class="font-bold text-sm">John Doe</div>
                <div class="text-xs text-gray-500">Head of Partnerships at Intercom</div>
            </div>
        </div>
    </div>
  </section>

  <!-- Features Section 2 (Blue) -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Build and run your <br /> campaign - at scale.
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 relative overflow-hidden">
                <!-- Kanban Board Mockup -->
                <div class="flex gap-4 h-full">
                    <div class="w-1/3 bg-white/50 rounded-lg p-2 space-y-2">
                        <div class="h-2 w-12 bg-blue-200 rounded"></div>
                        <div class="bg-white p-2 rounded shadow-sm h-16"></div>
                        <div class="bg-white p-2 rounded shadow-sm h-16"></div>
                    </div>
                    <div class="w-1/3 bg-white/50 rounded-lg p-2 space-y-2">
                        <div class="h-2 w-12 bg-blue-200 rounded"></div>
                         <div class="bg-white p-2 rounded shadow-sm h-16"></div>
                    </div>
                    <div class="w-1/3 bg-white/50 rounded-lg p-2 space-y-2">
                        <div class="h-2 w-12 bg-blue-200 rounded"></div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Design and run your campaign</h3>
            <p class="text-gray-500 text-sm">Build your perfect roster, then deploy and manage your creator campaign at scale from one integrated dash.</p>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                 <div class="bg-white rounded-xl shadow-lg p-4 w-3/4">
                    <div class="flex justify-between items-center mb-4">
                        <div class="h-3 w-20 bg-gray-200 rounded"></div>
                        <div class="h-6 w-20 bg-blue-500 rounded text-white text-[10px] flex items-center justify-center">Apply now</div>
                    </div>
                    <div class="space-y-2">
                        <div class="h-2 w-full bg-gray-100 rounded"></div>
                        <div class="h-2 w-5/6 bg-gray-100 rounded"></div>
                    </div>
                 </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Publish your own live campaign</h3>
            <p class="text-gray-500 text-sm">Tired of outreach? Publish your campaign with your creator requirements and let relevant creators apply and come to you!</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <!-- Calendar Mockup -->
                <div class="bg-white rounded-xl shadow-sm p-4 w-3/4">
                    <div class="grid grid-cols-7 gap-2 mb-2">
                        {#each Array(7) as _}
                            <div class="h-4 w-full bg-gray-100 rounded"></div>
                        {/each}
                    </div>
                    <div class="grid grid-cols-7 gap-2">
                        {#each Array(28) as _, i}
                            <div class="h-6 w-full {i === 14 ? 'bg-blue-500' : 'bg-gray-50'} rounded text-[8px] flex items-center justify-center text-gray-400">
                                {i === 14 ? 'Book' : ''}
                            </div>
                        {/each}
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Book ad slots directly</h3>
            <p class="text-gray-500 text-sm">Skip the scheduling back-and-forth - book open slots directly in creators' calendars.</p>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <!-- Chat Mockup -->
                <div class="w-full max-w-sm space-y-3">
                    <div class="flex gap-2">
                        <div class="w-8 h-8 bg-gray-200 rounded-full"></div>
                        <div class="bg-white p-3 rounded-2xl rounded-tl-none shadow-sm text-xs text-gray-500 w-2/3">
                            Hey! I'd love to work with you on this campaign.
                        </div>
                    </div>
                    <div class="flex gap-2 flex-row-reverse">
                        <div class="w-8 h-8 bg-blue-500 rounded-full"></div>
                        <div class="bg-blue-500 text-white p-3 rounded-2xl rounded-tr-none shadow-sm text-xs w-2/3">
                            Sounds great! Let's do it.
                        </div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Scale your outreach and connect directly in-app</h3>
            <p class="text-gray-500 text-sm">Passionfroot is not a database, it's the largest B2B creator network in the world. This means you can book all creators directly from your campaign. No more email outreach or ghosted DMs.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Thousands of campaigns -->
  <section class="py-24 bg-cream relative overflow-hidden">
    <!-- Floating Icons Background (Simplified) -->
    <div class="absolute inset-0 opacity-10 pointer-events-none">
        <div class="absolute top-10 left-10 w-12 h-12 bg-black rounded-lg transform rotate-12"></div>
        <div class="absolute top-20 right-20 w-12 h-12 bg-blue-500 rounded-lg transform -rotate-6"></div>
        <div class="absolute bottom-20 left-1/3 w-12 h-12 bg-pink-500 rounded-lg transform rotate-45"></div>
        <div class="absolute bottom-10 right-1/4 w-12 h-12 bg-orange-500 rounded-lg transform -rotate-12"></div>
    </div>

    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <div class="inline-block bg-green-100 text-green-800 px-4 py-1 rounded-full text-xs font-bold mb-6">
            Get on Passionfroot ->
        </div>
        <h2 class="text-4xl md:text-6xl font-serif mb-4">Thousands of campaigns <br /> launched to date</h2>
        <p class="text-gray-500 mb-10">with 60% lower CPC than LinkedIn Ads*</p>
        
        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Get access &rarr;</Button>
            <Button href="#" type="white">Talk to us</Button>
        </div>
    </div>
  </section>

  <!-- Payments Section (Green) -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Put creator payments & <br /> results on auto-pilot
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Left Large Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 md:row-span-2 flex flex-col">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Pay quickly and safely</h3>
                <p class="text-gray-500 text-sm">Pay one provider - not hundreds. Enjoy worldwide creator payments for seamless and secure transactions - your finance team will love you.</p>
            </div>
            <div class="flex-1 bg-green-50 rounded-2xl relative overflow-hidden min-h-[300px]">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_center,_var(--tw-gradient-stops))] from-green-200/50 to-transparent"></div>
                <!-- Globe/Map Abstract -->
                <div class="absolute inset-0 flex items-center justify-center">
                    <div class="w-64 h-64 border border-green-200 rounded-full opacity-50"></div>
                    <div class="w-48 h-48 border border-green-200 rounded-full opacity-50 absolute"></div>
                    <div class="w-96 h-96 border border-green-200 rounded-full opacity-30 absolute"></div>
                </div>
                <!-- Floating Avatars -->
                <div class="absolute top-1/4 left-1/4 bg-white p-1 rounded-full shadow-lg flex items-center gap-2 pr-3 animate-bounce">
                    <div class="w-8 h-8 bg-yellow-200 rounded-full"></div>
                    <span class="text-xs font-bold">$500</span>
                </div>
                <div class="absolute bottom-1/3 right-1/4 bg-white p-1 rounded-full shadow-lg flex items-center gap-2 pr-3 animate-bounce delay-700">
                    <div class="w-8 h-8 bg-blue-200 rounded-full"></div>
                    <span class="text-xs font-bold">$1200</span>
                </div>
            </div>
        </div>

        <!-- Right Top Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="flex justify-between items-start mb-4">
                <div>
                     <h3 class="text-xl font-serif mb-2">Measure returns effortlessly</h3>
                     <p class="text-gray-500 text-sm">Get results reported directly in your dash so you can take the guess work out of creator marketing.</p>
                </div>
                <span class="bg-green-100 text-green-700 px-2 py-1 rounded text-xs font-bold">Tracking live</span>
            </div>
            <div class="bg-green-50 rounded-xl h-40 flex items-end p-4 gap-2">
                <div class="w-1/5 bg-green-300 h-[40%] rounded-t"></div>
                <div class="w-1/5 bg-green-400 h-[60%] rounded-t"></div>
                <div class="w-1/5 bg-green-500 h-[30%] rounded-t"></div>
                <div class="w-1/5 bg-green-600 h-[80%] rounded-t"></div>
                <div class="w-1/5 bg-green-700 h-[50%] rounded-t"></div>
            </div>
        </div>

        <!-- Right Bottom Card (Testimonial) -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 flex gap-6 items-center">
            <div class="w-24 h-24 bg-gray-200 rounded-full flex-shrink-0 overflow-hidden">
                <!-- Placeholder for person -->
                <svg class="w-full h-full text-gray-400" fill="currentColor" viewBox="0 0 24 24"><path d="M24 24H0V0h24v24z" fill="none"/><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg>
            </div>
            <div>
                <div class="text-green-600 text-4xl font-serif leading-none mb-2">"</div>
                <p class="text-sm text-gray-600 italic mb-4">Passionfroot helped us streamline procurement and now automates our creator payouts globally. Our finance department loves it.</p>
                <div class="text-xs font-bold">Julia</div>
                <div class="text-[10px] text-gray-400">Senior Marketing Manager at Linktree</div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Powering People Grid -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Powering the people building category-defining brands
      </h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
         <!-- Row 1 -->
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
            <div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 transition-colors"></div>
            <div class="absolute bottom-4 left-4 text-white font-bold">Gamma</div>
            <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>
         <div class="aspect-square bg-white rounded-2xl flex items-center justify-center border border-gray-100">
            <span class="text-2xl font-bold flex items-center gap-2"><div class="w-6 h-6 bg-purple-500 rounded-tl-lg rounded-br-lg"></div> Figma</span>
         </div>
         <div class="col-span-2 bg-[#FFF9C4] rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-yellow-600">"</div>
            <p class="text-lg font-serif leading-relaxed">Partnering with creators through Passionfroot has been a strong growth channel. Instead of scouring the internet, their AI search enabled us to find...</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">John Doe</div>
                    <div class="text-gray-500">Head of Partnerships</div>
                </div>
                <div class="text-xl">+</div>
            </div>
         </div>

         <!-- Row 2 -->
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
            <span class="text-3xl font-bold text-gray-700">HubSpot</span>
         </div>
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <div class="absolute bottom-4 left-4 text-white font-bold">Munch</div>
             <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <div class="absolute bottom-4 left-4 text-white font-bold">Freshbooks</div>
             <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>

         <!-- Row 3 -->
         <div class="col-span-2 bg-[#E6F0FF] rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-blue-600">"</div>
            <p class="text-lg font-serif leading-relaxed">Passionfroot really helped us level up our creator program into a strong growth channel. Instead of scouring the internet...</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Jane Smith</div>
                    <div class="text-gray-500">Growth Lead</div>
                </div>
                <div class="text-xl">+</div>
            </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <span class="text-2xl font-bold flex items-center gap-2"><div class="w-6 h-6 bg-black rounded"></div> Framer</span>
         </div>
         
         <!-- Row 4 -->
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <div class="absolute bottom-4 left-4 text-white font-bold">Replit</div>
             <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <div class="absolute bottom-4 left-4 text-white font-bold">Pika</div>
             <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <span class="text-2xl font-bold">ElevenLabs</span>
         </div>
      </div>
    </div>
  </section>

  <!-- Orange CTA Section -->
  <section class="bg-orange-brand py-24 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <h2 class="text-4xl md:text-6xl font-serif mb-8 text-dark">Let's make creators your <br /> next growth channel</h2>
        
        <div class="flex flex-col md:flex-row justify-center gap-6 mb-10 text-sm font-medium text-dark/80">
            <div class="flex items-center gap-2">
                <div class="bg-dark text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Get better returns on your time & money
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-dark text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Save 70% of your time per campaign
            </div>
        </div>

        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Get access &rarr;</Button>
            <Button href="#" type="white">Talk to us</Button>
        </div>
    </div>

    <!-- Bottom Illustration (Cartoon Line) -->
    <div class="absolute bottom-0 left-0 right-0 h-32 opacity-20 pointer-events-none flex items-end justify-center overflow-hidden">
        <!-- Abstract representation of the cartoon line -->
        <svg width="1200" height="100" viewBox="0 0 1200 100" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M0 100 C 50 50, 100 50, 150 100" stroke="black" stroke-width="2" fill="none"/>
            <circle cx="75" cy="80" r="10" stroke="black" stroke-width="2"/>
            <path d="M150 100 C 200 60, 250 60, 300 100" stroke="black" stroke-width="2" fill="none"/>
            <circle cx="225" cy="85" r="12" stroke="black" stroke-width="2"/>
            <path d="M300 100 C 350 40, 400 40, 450 100" stroke="black" stroke-width="2" fill="none"/>
             <circle cx="375" cy="70" r="15" stroke="black" stroke-width="2"/>
             <!-- Repeat pattern -->
             <path d="M450 100 C 500 50, 550 50, 600 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M600 100 C 650 60, 700 60, 750 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M750 100 C 800 40, 850 40, 900 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M900 100 C 950 50, 1000 50, 1050 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M1050 100 C 1100 60, 1150 60, 1200 100" stroke="black" stroke-width="2" fill="none"/>
        </svg>
    </div>
  </section>

  <!-- Case Studies -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">Case Studies</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Large Card Top -->
        <div class="md:col-span-2 bg-[#FFCCBC] rounded-3xl p-10 md:p-16 flex flex-col md:flex-row items-center gap-10">
            <div class="flex-1">
                <div class="text-4xl font-bold text-white mb-8">guidde.</div>
            </div>
            <div class="flex-1 bg-white/90 backdrop-blur rounded-2xl p-8 shadow-sm">
                <div class="text-xs font-bold text-gray-400 uppercase mb-4">Customer Story</div>
                <h3 class="text-2xl font-serif mb-4">How Guidde made creators a scalable growth channel with Passionfroot</h3>
                <p class="text-gray-500 text-sm mb-6">Guidde is the generative AI platform for business that helps teams create video documentation in a matter...</p>
                <div class="flex justify-between items-center">
                    <span class="text-xs text-gray-400">4 min read</span>
                    <button class="bg-black text-white px-4 py-2 rounded-lg text-xs font-bold">Read more &rarr;</button>
                </div>
            </div>
        </div>

        <!-- Bottom Left -->
        <div class="bg-[#B3E5FC] rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="flex items-center gap-2 font-bold opacity-80 mb-8">
                <div class="w-6 h-6 bg-black rounded"></div> INTERCOM
            </div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Customer Story</div>
                <h3 class="text-xl font-serif mb-4">Becoming the definitive AI-first Customer Service Platform</h3>
                <div class="flex justify-between items-center mt-4">
                    <span class="text-xs text-gray-400">3 min read</span>
                    <button class="bg-black text-white px-3 py-1.5 rounded-lg text-xs font-bold">Read more &rarr;</button>
                </div>
            </div>
        </div>

        <!-- Bottom Right -->
        <div class="bg-[#FFCC80] rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="flex items-center gap-2 font-bold opacity-80 mb-8 text-blue-900">
                <div class="w-6 h-6 bg-blue-600 rounded"></div> Freshbooks
            </div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Customer Story</div>
                <h3 class="text-xl font-serif mb-4">How Freshbooks reached 2M+ impressions with Passionfroot</h3>
                <div class="flex justify-between items-center mt-4">
                    <span class="text-xs text-gray-400">3 min read</span>
                    <button class="bg-black text-white px-3 py-1.5 rounded-lg text-xs font-bold">Read more &rarr;</button>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif mb-16">Frequently Asked Questions</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-6">
        {#each [
            "What is Passionfroot?",
            "What types of businesses can use Passionfroot?",
            "How does Passionfroot work?",
            "What platforms can I use Passionfroot for?",
            "How do I discover the right creators for my brand?",
            "How are payments managed?",
            "Can I run multiple campaigns at once?",
            "How do I get started with Passionfroot?"
        ] as question}
            <div class="border-b border-gray-200 py-4 flex justify-between items-center group cursor-pointer">
                <span class="font-medium text-lg group-hover:text-orange-brand transition-colors">{question}</span>
                <div class="w-6 h-6 rounded-full bg-dark text-white flex items-center justify-center text-sm group-hover:bg-orange-brand transition-colors">+</div>
            </div>
        {/each}
      </div>
    </div>
  </section>

  <Footer />
</div>

<style>
  /* Custom Scroll Animation */
  @keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
  .animate-scroll {
    animation: scroll 20s linear infinite;
  }
  
  @keyframes spin-slow {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  .animate-spin-slow {
    animation: spin-slow 20s linear infinite;
  }
</style>

