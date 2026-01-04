<script lang="ts">
  // Hero component - Aura Financial inspired
</script>

<section class="px-6 pt-20 pb-12 md:pt-32 md:pb-20">
  <div class="max-w-7xl mx-auto">
    <!-- Hero Content -->
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 mb-20">
      <div class="flex flex-col justify-center">
        <div class="mb-6">
          <span class="inline-block text-[10px] tracking-[0.2em] text-gray-500 uppercase font-medium mb-8">
            Autonomous wealth creation
          </span>
        </div>
        <h1 class="text-5xl md:text-6xl lg:text-7xl leading-[1.05] tracking-tight text-gray-900 font-light mb-8">
          Private bank performance for everyone
        </h1>
        <p class="text-gray-600 text-lg leading-relaxed mb-10 max-w-xl">
          AI-managed, leveraged portfolios of tokenized real-world assets with on-chain protections and self-custody guarantees.
        </p>
        <div class="flex flex-col sm:flex-row items-start sm:items-center gap-4">
          <a href="/" class="bg-black text-white px-8 py-4 text-sm font-medium hover:bg-gray-800 transition-all duration-300 hover:scale-[1.02]">
            Start investing
          </a>
          <a href="/" class="text-sm text-gray-600 hover:text-black transition-colors flex items-center gap-2 group">
            Learn more
            <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
            </svg>
          </a>
        </div>
      </div>

      <!-- Stats Column -->
      <div class="flex flex-col justify-center gap-12 lg:pl-12">
        <div class="border-l-2 border-gray-200 pl-8">
          <div class="text-4xl md:text-5xl font-light text-gray-900 mb-2">$2.4B+</div>
          <div class="text-sm text-gray-500">Assets under management</div>
        </div>
        <div class="border-l-2 border-gray-200 pl-8">
          <div class="text-4xl md:text-5xl font-light text-gray-900 mb-2">15.2%</div>
          <div class="text-sm text-gray-500">Average annual returns</div>
        </div>
        <div class="border-l-2 border-gray-200 pl-8">
          <div class="text-4xl md:text-5xl font-light text-gray-900 mb-2">24/7</div>
          <div class="text-sm text-gray-500">Autonomous portfolio management</div>
        </div>
      </div>
    </div>

    <!-- Hero Image -->
    <div class="relative w-full h-[400px] md:h-[500px] lg:h-[600px] overflow-hidden bg-gray-900 rounded-lg">
      <img 
        src="/generated/image-modern-financial-technology-workspace-wi-1767518947858-0.webp" 
        alt="Financial technology and wealth management" 
        class="w-full h-full object-cover opacity-90"
      />
      
      <!-- Gradient Overlay -->
      <div class="absolute inset-0 bg-gradient-to-t from-gray-900/60 via-transparent to-transparent"></div>

      <!-- Floating Badge -->
      <div class="absolute bottom-8 left-8 bg-white/95 backdrop-blur-sm px-6 py-4 rounded-lg">
        <div class="flex items-center gap-3">
          <div class="w-2 h-2 bg-green-500 rounded-full animate-pulse"></div>
          <div>
            <div class="text-xs text-gray-500 mb-1">Live portfolio value</div>
            <div class="text-lg font-medium text-gray-900">$847,392.18</div>
          </div>
        </div>
      </div>

      <!-- Trust Indicators -->
      <div class="absolute top-8 right-8 flex flex-col gap-3">
        <div class="bg-white/95 backdrop-blur-sm px-4 py-2 rounded-lg text-xs text-gray-600 flex items-center gap-2">
          <svg class="w-4 h-4 text-green-600" fill="currentColor" viewBox="0 0 20 20">
            <path fill-rule="evenodd" d="M2.166 4.999A11.954 11.954 0 0010 1.944 11.954 11.954 0 0017.834 5c.11.65.166 1.32.166 2.001 0 5.225-3.34 9.67-8 11.317C5.34 16.67 2 12.225 2 7c0-.682.057-1.35.166-2.001zm11.541 3.708a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
          </svg>
          Self-custody
        </div>
        <div class="bg-white/95 backdrop-blur-sm px-4 py-2 rounded-lg text-xs text-gray-600 flex items-center gap-2">
          <svg class="w-4 h-4 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
            <path fill-rule="evenodd" d="M5 9V7a5 5 0 0110 0v2a2 2 0 012 2v5a2 2 0 01-2 2H5a2 2 0 01-2-2v-5a2 2 0 012-2zm8-2v2H7V7a3 3 0 016 0z" clip-rule="evenodd"/>
          </svg>
          On-chain protected
        </div>
      </div>
    </div>
  </div>
</section>
