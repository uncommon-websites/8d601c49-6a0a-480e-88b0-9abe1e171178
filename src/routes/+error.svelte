<script lang="ts">
	import { page } from "$app/stores";
</script>

<main class="min-h-screen bg-background text-foreground flex flex-col items-center justify-center p-8">
	<h1 class="text-4xl font-bold mb-4">Error {$page.status}</h1>
	<p class="text-muted mb-8">{$page.error?.message ?? "Something went wrong."}</p>
	<a href="/" class="bg-foreground text-background px-6 py-3 text-sm font-mono uppercase tracking-wider hover:bg-accent transition-colors">Go back home</a>
</main>
