<script lang="ts">
	import Counter from './Counter.svelte';
</script>

<div class="container">
	<slot />
	<Counter />
</div>

<style>
	.container {
		height: 500px;
		width: 500px;
		border: 6px dotted black;
		margin: auto;
		margin-top: 150px;
		text-align: center;
	}
</style>
