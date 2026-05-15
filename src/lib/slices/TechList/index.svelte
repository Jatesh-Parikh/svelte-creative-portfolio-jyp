<script lang="ts">
	import type { Content } from '@prismicio/client';

	export let slice: Content.TechListSlice;
</script>

<section data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	Placeholder component for {slice.slice_type} (variation: {slice.variation}) slices.
	<br />
	<strong>You can edit this slice directly in your code editor.</strong>
	<!--
	💡 Use the Prismic MCP server with your code editor
	📚 Docs: https://prismic.io/docs/ai#code-with-prismics-mcp-server
	-->
</section>
