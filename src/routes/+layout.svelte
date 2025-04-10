<script lang="ts">
	import type { Snippet } from "svelte";
	import "../app.css";

	let { children }: { children: Snippet } = $props();
</script>

<div class="flex justify-center items-center bg-gray-600 h-lvh">
	{@render children()}
</div>
