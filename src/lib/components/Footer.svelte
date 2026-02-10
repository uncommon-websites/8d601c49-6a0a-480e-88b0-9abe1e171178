<footer class="pt-20 pb-8">
	<div class="container-custom">
		<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-6 gap-12 mb-20">
			<!-- Logo Column -->
			<div class="lg:col-span-2">
				<a href="/" class="text-xl font-bold tracking-tight flex items-center gap-2 mb-4">
					<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-accent">
						<path d="M12 2L3 7V17L12 22L21 17V7L12 2Z" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/>
						<path d="M12 22V12" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/>
						<path d="M12 12L21 7" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/>
						<path d="M12 12L3 7" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/>
					</svg>
					<span class="font-sans font-semibold tracking-tighter">AGENTICAL LABS</span>
				</a>
				<p class="text-xs text-muted font-mono leading-relaxed max-w-[200px]">
					Validating the infrastructure of the agentic economy through public experimentation.
				</p>
			</div>

			<!-- Contact -->
			<div>
				<h4 class="font-mono text-xs uppercase text-muted mb-4 tracking-widest">Contact</h4>
				<ul class="space-y-2 text-xs font-mono text-muted">
					<li><a href="mailto:lab@agentical.xyz" class="hover:text-foreground">lab@agentical.xyz</a></li>
					<li><a href="#" class="hover:text-foreground">X / Twitter</a></li>
					<li><a href="#" class="hover:text-foreground">Discord</a></li>
				</ul>
			</div>

			<!-- Research -->
			<div>
				<h4 class="font-mono text-xs uppercase text-muted mb-4 tracking-widest">Research</h4>
				<ul class="space-y-2 text-xs font-mono text-muted">
					<li><a href="#" class="hover:text-foreground">Experiments</a></li>
					<li><a href="#" class="hover:text-foreground">Benchmarks</a></li>
					<li><a href="#" class="hover:text-foreground">Whitepapers</a></li>
					<li><a href="#" class="hover:text-foreground">Methodology</a></li>
					<li><a href="#" class="hover:text-foreground">Data Feeds</a></li>
				</ul>
			</div>

			<!-- Infrastructure -->
			<div>
				<h4 class="font-mono text-xs uppercase text-muted mb-4 tracking-widest">Infrastructure</h4>
				<ul class="space-y-2 text-xs font-mono text-muted">
					<li><a href="#" class="hover:text-foreground">Validated APIs</a></li>
					<li><a href="#" class="hover:text-foreground">Economic Primitives</a></li>
					<li><a href="#" class="hover:text-foreground">Coordination SDK</a></li>
					<li><a href="#" class="hover:text-foreground">Agent Funding</a></li>
					<li><a href="#" class="hover:text-foreground">Documentation</a></li>
				</ul>
			</div>

			<!-- Lab -->
			<div>
				<h4 class="font-mono text-xs uppercase text-muted mb-4 tracking-widest">Lab</h4>
				<ul class="space-y-2 text-xs font-mono text-muted mb-8">
					<li><a href="#" class="hover:text-foreground">About Us</a></li>
					<li><a href="#" class="hover:text-foreground">Team</a></li>
					<li><a href="#" class="hover:text-foreground">Careers</a></li>
					<li><a href="#" class="hover:text-foreground">Privacy</a></li>
					<li><a href="#" class="hover:text-foreground">Terms</a></li>
				</ul>
				
				<!-- Lab Badge -->
				<div class="w-16 h-16 border-2 border-accent rounded-full flex items-center justify-center relative">
					<div class="absolute inset-0 rounded-full border border-accent/20 m-0.5"></div>
					<div class="text-[8px] font-bold text-center leading-tight text-accent">
						PUBLIC<br>RESEARCH
					</div>
					<div class="absolute -bottom-1 -right-1 w-4 h-4 bg-accent rounded-full flex items-center justify-center text-white text-[8px]">✓</div>
				</div>
			</div>
		</div>

		<!-- Bottom Bar -->
		<div class="flex flex-col md:flex-row justify-between items-center gap-4 pt-8 border-t border-border font-mono text-[10px] text-muted uppercase tracking-widest">
			<div class="flex items-center gap-4">
				<div class="flex items-center gap-2">
					<span class="w-1.5 h-1.5 bg-accent rounded-full animate-pulse"></span>
					Lab Status: Active Experiments
				</div>
			</div>
			<div>
				Agentical Labs © 2025
			</div>
		</div>
	</div>

	<!-- Bottom Texture Strip -->
	<div class="mt-8 h-32 w-full bg-black relative overflow-hidden flex items-end justify-center pb-4">
		<!-- Noise Texture -->
		<div class="absolute inset-0 opacity-10" style="background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI0IiBoZWlnaHQ9IjQiPgo8cmVjdCB3aWR0aD0iNCIgaGVpZ2h0PSI0IiBmaWxsPSIjZmZmIi8+Cjwvc3ZnPg=='); background-size: 2px 2px;"></div>
		
		<!-- Glitch/Code Overlay -->
		<div class="absolute inset-0 opacity-20 font-mono text-[8px] text-accent overflow-hidden leading-none whitespace-pre-wrap break-all p-2 select-none pointer-events-none">
			{Array(2000).fill(0).map(() => Math.random() > 0.5 ? '1' : '0').join('')}
		</div>

		<div class="relative z-10 flex items-center gap-4 text-[10px] font-mono text-white/50">
			<div class="flex items-center gap-2 text-accent">
				<span class="w-2 h-2 bg-accent rounded-full"></span>
				AGENTIC ECONOMY
			</div>
			<div class="flex items-center gap-2">
				<span class="w-2 h-2 border border-white/50 rounded-full"></span>
				VALIDATED INFRA
			</div>
		</div>
	</div>
</footer>
