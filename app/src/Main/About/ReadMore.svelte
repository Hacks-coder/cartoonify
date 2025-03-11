<script>
	import Fill from "../Resuable/Buttons/Fill.svelte";
	import Title from "../Resuable/Text/Title.svelte";
    const readMore = "/bg/read-more.webp"
</script>
<section class="flex flex-col gap-5 items-center bg-cover bg-center h-70" style={`background-image: url(${readMore})`}>
    <Title text = "ABOUT US" />
    <p class="text-center">Welcome to our world of mythical creatures and epic tales! Our website is dedicated to bringing you captivating stories, breathtaking artwork, and unforgettable adventures. Whether you're a fan of fantasy, magic, or thrilling journeys, we aim to spark your imagination and transport you to realms beyond your wildest dreams</p>
    <Fill text = "Read More!" />
</section>