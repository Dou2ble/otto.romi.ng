<script lang="ts">
	import type { Snippet } from "svelte";

	let { children }: { children: Snippet } = $props();
</script>

<div class="flex justify-center items-center roundned-md bg-gray-800">
	{@render children()}
</div>
