<Index />

<script context="module">
	import something from '../something'
	import Index from './index.svelte'

	export async function preload() {
		return {something}
	}
</script>
