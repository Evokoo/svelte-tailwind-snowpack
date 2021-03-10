<script>
	let title = "Team";

	let team = [
		{name: "John Smith",
		 position: "Manager",
		 img: "/img/logo.svg"
		},
		{name: "Jane Doe",
		 position: "Manager"
		},
		{name: "Bob Billington",
		 position: "Manager"
		},
	]
</script>

<div class="w-full py-8">
	<h1 class="text-center text-4xl mb-8">{title}</h1>
	<div class="flex justify-around">
		{#each team as member}
		<div class="bg-yellow-300 w-1/3 mx-2 flex-col items-center">
			<img src="{member.img}" alt="" class="w-14 h-14">
			<h1>{member.name}</h1>
			<p>{member.position}</p>
		</div>
		{/each}
	</div>
</div>