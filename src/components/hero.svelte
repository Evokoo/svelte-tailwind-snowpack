<script>
	import { fade } from 'svelte/transition';
	let imgSrc = "https://source.unsplash.com/1920x1080/?space"

	let sum = 0;
	const add = () => sum++; 

</script>

<img src="{imgSrc}" alt="" class="h-auto w-auto">