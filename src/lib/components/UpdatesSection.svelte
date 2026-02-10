<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-16">
			
			<!-- Left Column: CTA & Visual -->
			<div class="flex flex-col h-full">
				<div class="mb-8">
					<p class="font-mono text-xs text-muted mb-4 uppercase tracking-widest">The Lab</p>
					<h2 class="text-3xl font-medium mb-4 tracking-tight">Building the economic <span class="italic">nervous system</span> for agents</h2>
					<p class="text-muted font-light mb-8 text-sm leading-relaxed max-w-md">
						Agentical Labs is validating the infrastructure, economic primitives, and coordination frameworks that will power the agentic economy.
					</p>
					<div class="flex gap-3 mb-12">
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							JOIN THE DISCORD
							<span class="text-muted border border-muted/30 rounded px-1 text-[9px] min-w-[16px] text-center">D</span>
						</button>
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							LATEST TRIALS
							<span class="text-muted border border-muted/30 rounded px-1 text-[9px] min-w-[16px] text-center">T</span>
						</button>
					</div>
				</div>
				
				<!-- Barcode Visual -->
				<div class="mt-auto w-full h-48 bg-black relative overflow-hidden flex items-center justify-center">
					{#each Array(100).fill(0) as _, i}
						<div 
							class="h-full bg-accent absolute" 
							style="
								left: {i}%; 
								width: {Math.random() * 2}%; 
								opacity: {Math.random() * 0.5};
							"
						></div>
					{/each}
					<div class="absolute inset-0 flex items-center justify-center">
						<div class="bg-black text-white font-mono text-[10px] px-2 py-1 z-10 border border-white/20">
							AGENTICAL.LABS // EXPERIMENT_LOG
						</div>
					</div>
				</div>
			</div>

			<!-- Right Column: Updates -->
			<div>
				<p class="font-mono text-xs text-muted mb-8 uppercase tracking-widest">Experiment Log</p>
				
				<div class="space-y-12">
					<!-- Update 1 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">Dec 04</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer uppercase">Autonomous Fund Deployment v2.4</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Successfully completed a 72-hour trial where 5 independent agents managed a shared treasury of 10 ETH, performing cross-chain swaps and liquidity provision with zero human intervention.
							</p>
							<span class="bg-primary-50 border border-primary-100 text-[10px] px-1.5 py-0.5 rounded text-accent font-mono">LIVE EXPERIMENT</span>
						</div>
					</div>

					<!-- Update 2 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">Nov 28</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer uppercase">Multi-Agent Coordination Latency</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Our latest benchmark compares 5 leading agent frameworks on communication overhead. Results show a 40% reduction in latency when using our validated RPC primitives.
							</p>
							<div class="flex gap-2">
								<span class="bg-primary-50 border border-primary-100 text-[10px] px-1.5 py-0.5 rounded text-accent font-mono">BENCHMARKS</span>
								<span class="bg-primary-50 border border-primary-100 text-[10px] px-1.5 py-0.5 rounded text-accent font-mono">RESEARCH</span>
							</div>
						</div>
					</div>

					<!-- Update 3 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">Nov 15</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer uppercase">Economic Primitives for Agentic Swarms</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Published a new whitepaper on "Proof of Contribution" models for autonomous agent swarms, detailing how to prevent sybil attacks in agentic economies.
							</p>
							<span class="bg-primary-50 border border-primary-100 text-[10px] px-1.5 py-0.5 rounded text-accent font-mono">WHITEPAPER</span>
						</div>
					</div>

					<!-- Update 4 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">Nov 01</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer uppercase">Agentical Labs Launch</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Opening the doors to the first research lab dedicated to building and testing agent infrastructure in public.
							</p>
							<span class="bg-primary-50 border border-primary-100 text-[10px] px-1.5 py-0.5 rounded text-accent font-mono">ANNOUNCEMENT</span>
						</div>
					</div>
				</div>
			</div>

		</div>
	</div>
</section>
