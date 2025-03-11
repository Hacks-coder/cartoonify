<script lang="ts">
	import '@fontsource/krona-one';
	import '@fontsource/inria-sans';
	import '../app.css';
	let { children } = $props();
</script>

<div class="bg-black text-sm text-white font-main">
	{@render children()}
</div>
