<script lang="ts">
	let count = 0;
</script>

<main>
	<div class="flex flex-col items-center">
		<div class="text-slate-600 text-9xl">{count}</div>
		<button class="text-slate-600 text-9xl bg-slate-300 p-3 rounded-lg" on:click={() => ++count}
			>Add</button
		>
	</div>
</main>
