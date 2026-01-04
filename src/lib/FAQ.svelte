<script lang="ts">
  // FAQ component - Clean, modern design
  let openIndex = $state<number | null>(null);

  const faqs = [
    {
      question: "How does autonomous portfolio management work?",
      answer: "Our AI continuously monitors market conditions, analyzes thousands of data points, and automatically rebalances your portfolio to optimize returns while managing risk. The system operates 24/7 without human intervention, executing trades and adjustments based on sophisticated algorithms."
    },
    {
      question: "What does self-custody mean for my investments?",
      answer: "Self-custody means you maintain complete control over your assets at all times. Your funds are held in smart contracts that only you can access with your private keys. We never have custody of your assets, eliminating counterparty risk entirely."
    },
    {
      question: "What are tokenized real-world assets?",
      answer: "Tokenized real-world assets are traditional assets like real estate, bonds, commodities, and equities that have been converted into blockchain tokens. This enables fractional ownership, instant liquidity, and 24/7 trading of assets that were previously illiquid or inaccessible."
    },
    {
      question: "What is the minimum investment required?",
      answer: "Minimum investments vary by strategy. Our Stable Yield portfolio starts at $10,000, Growth Portfolio at $25,000, and Maximum Returns at $50,000. These minimums ensure optimal portfolio diversification and cost efficiency."
    },
    {
      question: "How are returns generated and distributed?",
      answer: "Returns are generated through a combination of yield from tokenized assets, algorithmic trading, and leverage strategies. All returns are automatically reinvested or distributed according to your preferences, with real-time tracking available in your dashboard."
    },
    {
      question: "Is this platform regulated and compliant?",
      answer: "Yes, we operate in full compliance with relevant financial regulations. Our platform is SOC 2 Type II certified, and we work with licensed custodians and regulated exchanges. All tokenized assets are backed by real-world assets with proper legal frameworks."
    }
  ];

  function toggle(index: number) {
    openIndex = openIndex === index ? null : index;
  }
</script>

<section class="px-8 py-32 md:py-40 bg-white">
  <div class="max-w-[1400px] mx-auto">
    <div class="text-center mb-24 max-w-4xl mx-auto">
      <span class="text-[9px] tracking-[0.3em] text-gray-400 uppercase font-medium mb-10 block">
        Support
      </span>
      <h2 class="text-5xl md:text-6xl font-extralight text-gray-900 mb-10 leading-[1.05] tracking-tight">
        Frequently asked questions
      </h2>
      <p class="text-gray-500 text-lg md:text-xl leading-relaxed font-light">
        Have more questions? Our support team is available 24/7 to help you understand our platform and investment strategies.
      </p>
    </div>
      
    <div class="max-w-4xl mx-auto">
        <div class="space-y-4">
          {#each faqs as faq, i}
            <div class="border border-gray-200 rounded-lg overflow-hidden hover:border-gray-300 transition-colors">
              <button 
                class="w-full px-8 py-6 flex items-center justify-between text-left bg-white hover:bg-gray-50 transition-colors group"
                onclick={() => toggle(i)}
              >
                <span class="text-base font-medium text-gray-900 pr-8">{faq.question}</span>
                <div class={[
                  'flex-shrink-0 w-8 h-8 rounded-full border border-gray-300 flex items-center justify-center transition-all',
                  openIndex === i ? 'bg-gray-900 border-gray-900 rotate-180' : 'group-hover:border-gray-400'
                ]}>
                  <svg class={[
                    'w-4 h-4 transition-colors',
                    openIndex === i ? 'text-white' : 'text-gray-600'
                  ]} fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                  </svg>
                </div>
              </button>
              {#if openIndex === i}
                <div class="px-8 pb-6 text-gray-600 leading-relaxed animate-in fade-in slide-in-from-top-2 duration-200">
                  {faq.answer}
                </div>
              {/if}
            </div>
          {/each}
        </div>
      </div>
    </div>
  </div>
</section>
