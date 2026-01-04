<script lang="ts">
  // Founders Banner component - Professional styling
</script>

<section class="px-6 py-16 md:py-24">
  <div class="max-w-7xl mx-auto">
    <div class="relative overflow-hidden bg-gradient-to-br from-gray-900 via-gray-800 to-gray-900 rounded-2xl">
      <!-- Background Pattern -->
      <div class="absolute inset-0 opacity-10">
        <svg class="w-full h-full" viewBox="0 0 100 100" preserveAspectRatio="none">
          <defs>
            <pattern id="grid" width="10" height="10" patternUnits="userSpaceOnUse">
              <path d="M 10 0 L 0 0 0 10" fill="none" stroke="white" stroke-width="0.5"/>
            </pattern>
          </defs>
          <rect width="100" height="100" fill="url(#grid)" />
        </svg>
      </div>

      <div class="relative z-10 grid grid-cols-1 lg:grid-cols-2 gap-12 p-12 md:p-16 lg:p-20">
        <!-- Content -->
        <div class="flex flex-col justify-center">
          <span class="text-[10px] tracking-[0.2em] text-gray-400 uppercase font-medium mb-6 block">
            For institutions
          </span>
          <h2 class="text-3xl md:text-4xl lg:text-5xl font-light text-white mb-6 leading-[1.1]">
            Enterprise-grade wealth management infrastructure
          </h2>
          <p class="text-gray-300 text-lg leading-relaxed mb-8">
            White-label our autonomous investment platform for your clients. Deliver private-bank performance at scale with complete brand customization and regulatory compliance.
          </p>
          <div class="flex flex-col sm:flex-row gap-4">
            <a href="/" class="inline-flex items-center justify-center bg-white text-gray-900 px-8 py-4 text-sm font-medium hover:bg-gray-100 transition-all duration-300 hover:scale-[1.02]">
              Schedule a demo
            </a>
            <a href="/" class="inline-flex items-center justify-center border border-white/20 text-white px-8 py-4 text-sm font-medium hover:bg-white/10 transition-colors">
              View case studies
            </a>
          </div>
        </div>

        <!-- Stats -->
        <div class="flex flex-col justify-center gap-8 lg:pl-12">
          <div class="border-l-2 border-white/20 pl-6">
            <div class="text-3xl md:text-4xl font-light text-white mb-2">50+</div>
            <div class="text-sm text-gray-400">Financial institutions partnered</div>
          </div>
          <div class="border-l-2 border-white/20 pl-6">
            <div class="text-3xl md:text-4xl font-light text-white mb-2">$8.2B</div>
            <div class="text-sm text-gray-400">Total platform AUM</div>
          </div>
          <div class="border-l-2 border-white/20 pl-6">
            <div class="text-3xl md:text-4xl font-light text-white mb-2">99.9%</div>
            <div class="text-sm text-gray-400">Platform uptime guarantee</div>
          </div>
        </div>
      </div>

      <!-- Trust Badges -->
      <div class="relative z-10 border-t border-white/10 px-12 md:px-16 lg:px-20 py-8">
        <div class="flex flex-wrap items-center justify-between gap-6 text-xs text-gray-400">
          <div class="flex items-center gap-2">
            <svg class="w-4 h-4 text-green-500" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M2.166 4.999A11.954 11.954 0 0010 1.944 11.954 11.954 0 0017.834 5c.11.65.166 1.32.166 2.001 0 5.225-3.34 9.67-8 11.317C5.34 16.67 2 12.225 2 7c0-.682.057-1.35.166-2.001zm11.541 3.708a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
            </svg>
            <span>SOC 2 Type II Certified</span>
          </div>
          <div class="flex items-center gap-2">
            <svg class="w-4 h-4 text-blue-500" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M5 9V7a5 5 0 0110 0v2a2 2 0 012 2v5a2 2 0 01-2 2H5a2 2 0 01-2-2v-5a2 2 0 012-2zm8-2v2H7V7a3 3 0 016 0z" clip-rule="evenodd"/>
            </svg>
            <span>Bank-grade encryption</span>
          </div>
          <div class="flex items-center gap-2">
            <svg class="w-4 h-4 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
              <path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z"/>
              <path fill-rule="evenodd" d="M4 5a2 2 0 012-2 3 3 0 003 3h2a3 3 0 003-3 2 2 0 012 2v11a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm3 4a1 1 0 000 2h.01a1 1 0 100-2H7zm3 0a1 1 0 000 2h3a1 1 0 100-2h-3zm-3 4a1 1 0 100 2h.01a1 1 0 100-2H7zm3 0a1 1 0 100 2h3a1 1 0 100-2h-3z" clip-rule="evenodd"/>
            </svg>
            <span>Regulatory compliant</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
