<script lang="ts">
	import Footer from '../../Footer/Footer.svelte';
	import Header from '../../Header/Header.svelte';
	import Hero from '../../Main/others/Hero.svelte';

    const heroBg = "/bg/hero.webp"

	let { children } = $props();
</script>

<div class="@container">
    <div class="bg-cover bg-center p-2 h-70 w-full" style={`background-image: url(${heroBg})`}>
        <Header />
        <Hero />
    </div>
    {@render children()}
    <Footer />
</div>
