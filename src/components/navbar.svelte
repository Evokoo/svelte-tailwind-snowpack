<script>

	let menu = [
		{title: 'home', url:"#home"},
		{title: 'about', url:"#about"}
	]
</script>


<div class="bg-yellow-300 w-screen h-16 flex">
	<img class="justify-center" src="/img/logo.svg" alt=""> 
	<ul class="flex items-center">
	{#each menu as item}
	<li class="mr-2 font-semibold text-yellow-500 hover:text-yellow-600"><a href="{item.url}">{item.title}</a></li>
	{/each}
	</ul>
</div>