<script>
	import { onMount } from 'svelte';
	import { createScene } from "./scene.js";

	let el;

	onMount(() => {
		createScene(el)
	});
</script>

<canvas bind:this={el}></canvas>