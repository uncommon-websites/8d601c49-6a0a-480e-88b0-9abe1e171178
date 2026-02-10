<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="flex flex-col md:flex-row justify-between items-start mb-16 gap-8">
			<div>
				<h2 class="text-3xl font-medium mb-2 tracking-tight uppercase">Validated Performance Benchmarks</h2>
				<p class="text-xl text-muted font-light">Measuring coordination efficiency across agentic frameworks</p>
			</div>
			<div class="max-w-xs text-[10px] text-muted leading-relaxed border-l border-border pl-4">
				<strong class="text-foreground block mb-1 uppercase tracking-widest">About this benchmark</strong>
				This test measures the communication overhead and success rate of multi-agent systems performing complex economic tasks (e.g., cross-chain arbitrage, resource negotiation). Agentical Labs' validated primitives reduce redundant calls and optimize for settlement speed.
			</div>
		</div>

		<div class="relative w-full h-[500px] border border-border bg-primary-50/10 p-8 font-mono text-xs">
			<!-- Chart Grid -->
			<div class="absolute inset-0 p-8 grid grid-rows-6 grid-cols-1">
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
				<div class="border-b border-dashed border-gray-200 w-full h-full"></div>
			</div>
			
			<!-- Y Axis Label -->
			<div class="absolute left-2 top-1/2 -translate-y-1/2 -rotate-90 text-muted origin-center whitespace-nowrap uppercase tracking-widest">
				Success Rate (%)
			</div>

			<!-- X Axis Label -->
			<div class="absolute bottom-2 left-1/2 -translate-x-1/2 text-muted uppercase tracking-widest">
				Coordination Latency (ms)
			</div>

			<!-- Top Left Legend -->
			<div class="absolute top-4 left-4 flex gap-4 text-[10px] text-muted uppercase tracking-tighter">
				<span class="bg-accent/10 text-accent px-1 rounded">Agentical V1</span>
				<span>Standard RPC</span>
				<span>P2P Mesh</span>
				<span>Centralized Hub</span>
			</div>

			<!-- Data Points -->
			
			<!-- Agentical Labs (The Winner) -->
			<div class="absolute top-[10%] left-[10%] flex flex-col items-center group cursor-pointer z-10">
				<div class="flex items-center gap-2 mb-1">
					<span class="text-accent font-bold uppercase">Agentical Labs</span>
				</div>
				<div class="w-4 h-4 bg-accent rounded-full shadow-[0_0_0_6px_rgba(oklch(0.623_0.214_259.815)/0.2)]"></div>
				<div class="mt-1 text-[10px] text-accent font-bold">98% / 120ms</div>
			</div>

			<!-- CrewAI -->
			<div class="absolute top-[35%] left-[45%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold uppercase">CrewAI</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">82% / 450ms</div>
			</div>

			<!-- LangChain -->
			<div class="absolute top-[50%] left-[35%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px] uppercase">LangChain</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">75% / 380ms</div>
			</div>

			<!-- Fetch.ai -->
			<div class="absolute top-[65%] left-[60%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px] uppercase">Fetch.ai</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">68% / 620ms</div>
			</div>

			<!-- AutoGPT -->
			<div class="absolute top-[80%] right-[15%] flex flex-col items-center group cursor-pointer">
				<div class="flex items-center gap-2 mb-1 opacity-100">
					<span class="font-bold text-[10px] uppercase">AutoGPT</span>
				</div>
				<div class="w-2 h-2 bg-black rounded-full"></div>
				<div class="mt-1 text-[10px] text-muted">45% / 1200ms</div>
			</div>

			<!-- Bottom Right Legend -->
			<div class="absolute bottom-4 right-4 flex items-center gap-4 text-[10px] uppercase font-mono">
				<div class="flex items-center gap-1">
					<div class="w-2 h-2 bg-accent rounded-full"></div>
					<span class="text-accent font-bold">Agentical Labs</span>
				</div>
				<div class="flex items-center gap-1">
					<div class="w-2 h-2 bg-black rounded-full"></div>
					<span class="text-muted">Industry Standard</span>
				</div>
			</div>
		</div>
	</div>
</section>
