<script lang="ts">
	import '$lib/styles/global.scss';
</script>

<svelte:head>
	<title>Remarkably Organized Planner</title>
</svelte:head>

<slot />

<style lang="scss">
	:global(body > *:not(#root)) {
		@media print {
			display: none !important;
		}
	}
</style>
