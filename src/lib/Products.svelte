<script lang="ts">
  // Products component - Sophisticated grid layout
</script>

<section class="px-6 py-24 md:py-32 bg-gray-50">
  <div class="max-w-[1400px] mx-auto">
    <div class="text-center mb-24 max-w-4xl mx-auto">
      <span class="text-[9px] tracking-[0.3em] text-gray-400 uppercase font-medium mb-10 block">
        Investment strategies
      </span>
      <h2 class="text-5xl md:text-6xl font-extralight text-gray-900 mb-10 max-w-3xl mx-auto leading-[1.05] tracking-tight">
        Diversified portfolios designed for sustainable growth
      </h2>
      <p class="text-gray-500 text-lg md:text-xl max-w-2xl mx-auto leading-relaxed font-light">
        Choose from our range of AI-managed strategies, each optimized for different risk profiles and investment horizons.
      </p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
      <!-- Strategy 1 -->
      <div class="bg-white border border-gray-200 p-8 hover:border-gray-900 transition-all duration-300 group cursor-pointer">
        <div class="flex items-start justify-between mb-8">
          <span class="text-[9px] text-gray-400 tracking-[0.3em] uppercase font-medium">Conservative</span>
        </div>
        <h3 class="text-3xl font-extralight text-gray-900 mb-4 tracking-tight">Stable yield</h3>
        <p class="text-gray-500 text-sm leading-relaxed mb-8 font-light">
          Low-volatility strategy focused on consistent returns through diversified tokenized bonds and real estate.
        </p>
        <div class="border-t border-gray-100 pt-6 space-y-4">
          <div class="flex justify-between text-sm">
            <span class="text-gray-400 font-light">Target APY</span>
            <span class="font-light text-gray-900">8-12%</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-400 font-light">Risk level</span>
            <span class="font-light text-gray-900">Low</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-400 font-light">Min. investment</span>
            <span class="font-light text-gray-900">$10,000</span>
          </div>
        </div>
        <div class="mt-8">
          <div class="text-sm text-gray-500 group-hover:text-gray-900 font-light group-hover:gap-2 flex items-center gap-1 transition-all duration-300">
            Learn more
            <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M9 5l7 7-7 7"/>
            </svg>
          </div>
        </div>
      </div>

      <!-- Strategy 2 -->
      <div class="bg-white border border-gray-200 p-10 hover:border-gray-400 transition-all duration-500 group cursor-pointer">
        <div class="flex items-start justify-between mb-8">
          <span class="text-[9px] text-gray-400 tracking-[0.3em] uppercase font-medium">Balanced</span>
        </div>
        <h3 class="text-3xl font-extralight text-gray-900 mb-4 tracking-tight">Growth portfolio</h3>
        <p class="text-gray-500 text-sm leading-relaxed mb-8 font-light">
          Balanced approach combining stable assets with growth opportunities in tokenized equities and commodities.
        </p>
        <div class="border-t border-gray-100 pt-6 space-y-4">
          <div class="flex justify-between text-sm">
            <span class="text-gray-400 font-light">Target APY</span>
            <span class="font-light text-gray-900">15-22%</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-400 font-light">Risk level</span>
            <span class="font-light text-gray-900">Medium</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-400 font-light">Min. investment</span>
            <span class="font-light text-gray-900">$25,000</span>
          </div>
        </div>
        <div class="mt-8">
          <div class="text-sm text-gray-500 group-hover:text-gray-900 font-light group-hover:gap-2 flex items-center gap-1 transition-all duration-300">
            Learn more
            <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M9 5l7 7-7 7"/>
            </svg>
          </div>
        </div>
      </div>

      <!-- Strategy 3 -->
      <div class="bg-white border border-gray-200 p-10 hover:border-gray-400 transition-all duration-500 group cursor-pointer">
        <div class="flex items-start justify-between mb-8">
          <span class="text-[9px] text-gray-400 tracking-[0.3em] uppercase font-medium">Aggressive</span>
        </div>
        <h3 class="text-3xl font-extralight text-gray-900 mb-4 tracking-tight">Maximum returns</h3>
        <p class="text-gray-500 text-sm leading-relaxed mb-8 font-light">
          High-leverage strategy targeting exceptional returns through algorithmic trading and emerging asset classes.
        </p>
        <div class="border-t border-gray-200 pt-6 space-y-3">
          <div class="flex justify-between text-sm">
            <span class="text-gray-500">Target APY</span>
            <span class="font-medium text-gray-900">25-40%</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-500">Risk level</span>
            <span class="font-medium text-gray-900">High</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-500">Min. investment</span>
            <span class="font-medium text-gray-900">$50,000</span>
          </div>
        </div>
        <div class="mt-6">
          <div class="text-sm text-gray-900 font-medium group-hover:gap-2 flex items-center gap-1 transition-all">
            Learn more
            <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
            </svg>
          </div>
        </div>
      </div>
    </div>

    <!-- CTA Banner -->
    <div class="mt-12 bg-gray-900 p-12 rounded-lg text-center">
      <h3 class="text-3xl md:text-4xl font-extralight text-white mb-6 tracking-tight">
        Not sure which strategy fits your goals?
      </h3>
      <p class="text-gray-400 mb-10 max-w-2xl mx-auto font-light text-lg">
        Our AI advisor can help you choose the optimal portfolio based on your risk tolerance, investment timeline, and financial objectives.
      </p>
      <a href="/" class="inline-block bg-white text-gray-900 px-10 py-5 text-sm font-medium tracking-wide hover:bg-gray-100 transition-all duration-300">
        Get personalized recommendations
      </a>
    </div>
  </div>
</section>
 on your risk tolerance, investment timeline, and financial objectives.
      </p>
      <a href="/" class="inline-block bg-white text-gray-900 px-8 py-4 text-sm font-medium hover:bg-gray-100 transition-colors">
        Get personalized recommendations
      </a>
    </div>
  </div>
</section>
