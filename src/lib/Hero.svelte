<script lang="ts">
  // Hero component - Ultra-minimal Aura-inspired design
</script>

<section class="px-6 pt-32 pb-24 md:pt-40 md:pb-32">
  <div class="max-w-[1400px] mx-auto">
    <!-- Hero Content -->
    <div class="max-w-4xl mx-auto text-center mb-24">
      <div class="mb-10">
        <span class="inline-block text-[9px] tracking-[0.3em] text-gray-400 uppercase font-medium">
          Autonomous wealth creation
        </span>
      </div>
      <h1 class="text-6xl md:text-7xl lg:text-8xl leading-[0.95] tracking-[-0.02em] text-gray-900 font-extralight mb-12">
        Private bank performance for everyone
      </h1>
      <p class="text-gray-500 text-xl md:text-2xl leading-relaxed mb-16 max-w-3xl mx-auto font-light">
        AI-managed, leveraged portfolios of tokenized real-world assets with on-chain protections and self-custody guarantees.
      </p>
      <div class="flex flex-col sm:flex-row items-center justify-center gap-5">
        <a href="/" class="bg-black text-white px-10 py-5 text-sm font-medium tracking-wide hover:bg-gray-900 transition-all duration-500">
          Start investing
        </a>
        <a href="/" class="text-sm text-gray-500 hover:text-gray-900 transition-colors duration-300 flex items-center gap-2 group">
          Learn more
          <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M9 5l7 7-7 7"/>
          </svg>
        </a>
      </div>
    </div>

    <!-- Stats Row -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-16 mb-32 max-w-5xl mx-auto">
      <div class="text-center">
        <div class="text-5xl md:text-6xl font-extralight text-gray-900 mb-3 tracking-tight">$2.4B+</div>
        <div class="text-sm text-gray-400 tracking-wide">Assets under management</div>
      </div>
      <div class="text-center">
        <div class="text-5xl md:text-6xl font-extralight text-gray-900 mb-3 tracking-tight">15.2%</div>
        <div class="text-sm text-gray-400 tracking-wide">Average annual returns</div>
      </div>
      <div class="text-center">
        <div class="text-5xl md:text-6xl font-extralight text-gray-900 mb-3 tracking-tight">24/7</div>
        <div class="text-sm text-gray-400 tracking-wide">Autonomous management</div>
      </div>
    </div>

    <!-- Hero Image -->
    <div class="relative w-full h-[500px] md:h-[600px] lg:h-[700px] overflow-hidden bg-gray-100">
      <img 
        src="/generated/image-modern-financial-technology-workspace-wi-1767518947858-0.webp" 
        alt="Financial technology and wealth management" 
        class="w-full h-full object-cover"
      />
      
      <!-- Minimal Overlay -->
      <div class="absolute inset-0 bg-gradient-to-t from-white/40 via-transparent to-transparent"></div>

      <!-- Floating Badge -->
      <div class="absolute bottom-10 left-10 bg-white px-8 py-5 border border-gray-200">
        <div class="flex items-center gap-4">
          <div class="w-2 h-2 bg-green-500 rounded-full"></div>
          <div>
            <div class="text-[10px] text-gray-400 mb-1 tracking-wider uppercase">Live portfolio value</div>
            <div class="text-xl font-light text-gray-900 tracking-tight">$847,392.18</div>
          </div>
        </div>
      </div>

      <!-- Trust Indicators -->
      <div class="absolute top-10 right-10 flex flex-col gap-3">
        <div class="bg-white px-5 py-3 border border-gray-200 text-xs text-gray-500 flex items-center gap-2 tracking-wide">
          <svg class="w-4 h-4 text-green-600" fill="currentColor" viewBox="0 0 20 20">
            <path fill-rule="evenodd" d="M2.166 4.999A11.954 11.954 0 0010 1.944 11.954 11.954 0 0017.834 5c.11.65.166 1.32.166 2.001 0 5.225-3.34 9.67-8 11.317C5.34 16.67 2 12.225 2 7c0-.682.057-1.35.166-2.001zm11.541 3.708a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
          </svg>
          Self-custody
        </div>
        <div class="bg-white px-5 py-3 border border-gray-200 text-xs text-gray-500 flex items-center gap-2 tracking-wide">
          <svg class="w-4 h-4 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
            <path fill-rule="evenodd" d="M5 9V7a5 5 0 0110 0v2a2 2 0 012 2v5a2 2 0 01-2 2H5a2 2 0 01-2-2v-5a2 2 0 012-2zm8-2v2H7V7a3 3 0 016 0z" clip-rule="evenodd"/>
          </svg>
          On-chain protected
        </div>
      </div>
    </div>
  </div>
</section>
