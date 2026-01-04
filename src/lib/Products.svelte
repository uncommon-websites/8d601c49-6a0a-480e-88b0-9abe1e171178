<script lang="ts">
  // Products component - Sophisticated grid layout
</script>

<section class="px-6 py-24 md:py-32 bg-gray-50">
  <div class="max-w-7xl mx-auto">
    <div class="mb-16">
      <span class="text-[10px] tracking-[0.2em] text-gray-500 uppercase font-medium mb-6 block">
        Investment strategies
      </span>
      <h2 class="text-4xl md:text-5xl font-light text-gray-900 mb-6 max-w-3xl leading-[1.1]">
        Diversified portfolios designed for sustainable growth
      </h2>
      <p class="text-gray-600 text-lg max-w-2xl leading-relaxed">
        Choose from our range of AI-managed strategies, each optimized for different risk profiles and investment horizons.
      </p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
      <!-- Strategy 1 -->
      <div class="bg-white border border-gray-200 p-8 hover:border-gray-900 transition-all duration-300 group cursor-pointer">
        <div class="flex items-start justify-between mb-6">
          <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center">
            <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"/>
            </svg>
          </div>
          <span class="text-xs text-gray-500 bg-gray-100 px-3 py-1 rounded-full">Conservative</span>
        </div>
        <h3 class="text-2xl font-medium text-gray-900 mb-3">Stable yield</h3>
        <p class="text-gray-600 text-sm leading-relaxed mb-6">
          Low-volatility strategy focused on consistent returns through diversified tokenized bonds and real estate.
        </p>
        <div class="border-t border-gray-200 pt-6 space-y-3">
          <div class="flex justify-between text-sm">
            <span class="text-gray-500">Target APY</span>
            <span class="font-medium text-gray-900">8-12%</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-500">Risk level</span>
            <span class="font-medium text-gray-900">Low</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-500">Min. investment</span>
            <span class="font-medium text-gray-900">$10,000</span>
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

      <!-- Strategy 2 -->
      <div class="bg-white border border-gray-200 p-8 hover:border-gray-900 transition-all duration-300 group cursor-pointer">
        <div class="flex items-start justify-between mb-6">
          <div class="w-12 h-12 bg-purple-600 rounded-lg flex items-center justify-center">
            <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"/>
            </svg>
          </div>
          <span class="text-xs text-gray-500 bg-gray-100 px-3 py-1 rounded-full">Balanced</span>
        </div>
        <h3 class="text-2xl font-medium text-gray-900 mb-3">Growth portfolio</h3>
        <p class="text-gray-600 text-sm leading-relaxed mb-6">
          Balanced approach combining stable assets with growth opportunities in tokenized equities and commodities.
        </p>
        <div class="border-t border-gray-200 pt-6 space-y-3">
          <div class="flex justify-between text-sm">
            <span class="text-gray-500">Target APY</span>
            <span class="font-medium text-gray-900">15-22%</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-500">Risk level</span>
            <span class="font-medium text-gray-900">Medium</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-500">Min. investment</span>
            <span class="font-medium text-gray-900">$25,000</span>
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

      <!-- Strategy 3 -->
      <div class="bg-white border border-gray-200 p-8 hover:border-gray-900 transition-all duration-300 group cursor-pointer">
        <div class="flex items-start justify-between mb-6">
          <div class="w-12 h-12 bg-orange-600 rounded-lg flex items-center justify-center">
            <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
            </svg>
          </div>
          <span class="text-xs text-gray-500 bg-gray-100 px-3 py-1 rounded-full">Aggressive</span>
        </div>
        <h3 class="text-2xl font-medium text-gray-900 mb-3">Maximum returns</h3>
        <p class="text-gray-600 text-sm leading-relaxed mb-6">
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
      <h3 class="text-2xl md:text-3xl font-light text-white mb-4">
        Not sure which strategy fits your goals?
      </h3>
      <p class="text-gray-400 mb-8 max-w-2xl mx-auto">
        Our AI advisor can help you choose the optimal portfolio based on your risk tolerance, investment timeline, and financial objectives.
      </p>
      <a href="/" class="inline-block bg-white text-gray-900 px-8 py-4 text-sm font-medium hover:bg-gray-100 transition-colors">
        Get personalized recommendations
      </a>
    </div>
  </div>
</section>
