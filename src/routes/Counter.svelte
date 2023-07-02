<script lang="ts">
	let count = 0;
</script>

<button on:click={() => count++}>
	Clicked {count}
	{count === 1 ? 'time' : 'times'}
</button>
