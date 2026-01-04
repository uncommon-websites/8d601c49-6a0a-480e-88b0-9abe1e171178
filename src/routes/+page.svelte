<script>
  import Header from "$lib/Header.svelte";
  import Hero from "$lib/Hero.svelte";
  import Logos from "$lib/Logos.svelte";
  import WhyEcho from "$lib/WhyEcho.svelte";
  import Products from "$lib/Products.svelte";
  import FoundersBanner from "$lib/FoundersBanner.svelte";
  import FAQ from "$lib/FAQ.svelte";
  import FooterCTA from "$lib/FooterCTA.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<div class="min-h-screen bg-white font-sans selection:bg-black selection:text-white">
  <Header />
  
  <main>
    <Hero />
    <Logos />
    <WhyEcho />
    <Products />
    <FoundersBanner />
    <FAQ />
    <FooterCTA />
  </main>

  <Footer />
</div>

