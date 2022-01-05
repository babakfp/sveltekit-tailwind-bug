<script>
	import Comp from '$lib/Comp.svelte'
</script>

<div class="content">CONTENT</div>

<div>
	<Comp class="my-content">MY CONTENT</Comp>
</div>

<style lang="postcss">
	div :global(.my-content) {
		@apply flex items-center justify-center w-full h-20 border-2 border-red-500 border-dashed uppercase;
	}
</style>
