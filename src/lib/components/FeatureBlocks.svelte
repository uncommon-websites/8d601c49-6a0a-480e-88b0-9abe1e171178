<script lang="ts">
	import FeatureBlock from './FeatureBlock.svelte';
</script>

<!-- Block 1: Public Experiments -->
<FeatureBlock 
	title="Public Experiments, not private claims" 
	description="We test infrastructure out in the open so the community can learn from real-world performance data."
	buttons={[
		{ text: "VIEW LIVE EXPERIMENTS", icon: true },
		{ text: "METHODOLOGY" }
	]}
>
	<div class="w-full h-full relative bg-white border border-border rounded shadow-sm overflow-hidden group">
		<img 
			src="/generated/image-close-up-of-a-high-end-computer-screen-s-1770719555111-1.webp" 
			alt="Public Experiment Dashboard" 
			class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500"
		/>
		<div class="absolute top-4 left-4 font-mono text-[10px] bg-black/80 text-white px-2 py-1 backdrop-blur-sm">
			LIVE_FEED: AGENT_NODE_04
		</div>
	</div>
</FeatureBlock>

<!-- Block 2: Validated Infrastructure -->
<FeatureBlock 
	title="Validated Infrastructure" 
	description="Once a pattern is proven in our lab, we productize it into robust APIs and frameworks for the ecosystem."
	buttons={[
		{ text: "EXPLORE THE STACK", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full h-full relative bg-white border border-border rounded shadow-sm overflow-hidden group">
		<img 
			src="/generated/image-a-sleek-modern-server-rack-in-a-dimly-li-1770719562363-3.webp" 
			alt="Validated Infrastructure" 
			class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500"
		/>
		<div class="absolute bottom-4 right-4 font-mono text-[10px] bg-accent text-white px-2 py-1">
			INFRA_STATUS: OPTIMIZED
		</div>
	</div>
</FeatureBlock>

<!-- Block 3: Agentic Economy -->
<FeatureBlock 
	title="The Agentic Economy" 
	description="We're building the economic primitives—funding, incentives, and settlement—that allow agents to operate autonomously."
	buttons={[
		{ text: "READ ECONOMIC PAPERS", icon: true }
	]}
>
	<div class="w-full h-full relative bg-white border border-border rounded shadow-sm overflow-hidden group">
		<img 
			src="/generated/image-an-abstract-clean-visualization-of-inter-1770719559781-2.webp" 
			alt="Economic Primitives Visualization" 
			class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500"
		/>
		<div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 font-mono text-[10px] bg-white/90 text-black border border-border px-3 py-2 backdrop-blur-sm uppercase tracking-widest">
			Economic Primitive v1.0
		</div>
	</div>
</FeatureBlock>

<!-- Block 4: Open Research -->
<FeatureBlock 
	title="Open Research & Benchmarks" 
	description="No more fragmented tools or unclear best practices. We publish benchmarks that matter for production-grade agents."
	buttons={[
		{ text: "ACCESS BENCHMARKS", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-4 flex flex-col gap-4">
		<div class="flex items-center justify-between border-b border-border pb-2">
			<div class="text-[10px] font-mono text-muted flex items-center gap-2 uppercase tracking-tighter">
				<span class="w-2 h-2 bg-accent rounded-full"></span>
				Latest Benchmark: Multi-Agent Coordination Latency
			</div>
		</div>
		
		<div class="space-y-4">
			<div class="flex items-end gap-1 h-24">
				{#each [40, 70, 45, 90, 65, 80, 55, 75, 95, 60] as height}
					<div class="flex-1 bg-primary-100 hover:bg-accent transition-colors cursor-pointer" style="height: {height}%"></div>
				{/each}
			</div>
			<div class="flex justify-between text-[8px] font-mono text-muted uppercase">
				<span>Framework A</span>
				<span>Framework B</span>
				<span>Agentical V1</span>
			</div>
		</div>
	</div>
</FeatureBlock>
