<script lang="ts">
	import Header from '../../Header/Header.svelte';
	import Hero from '../../Main/others/Hero.svelte';

	let { children } = $props();
</script>

<div>
    <div>
        <Header />
        <Hero />
    </div>
    {@render children()}
</div>
