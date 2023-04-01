<script>
	import { page } from '$app/stores';

	const slugArr = $page.params.slug.split('/');
</script>

{#if slugArr.length === 1}
	<h1>Docs for Feature {slugArr[0]}.</h1>
{:else if slugArr.length === 2}
	<h1>Docs for Feature {slugArr[0]} and Concept {slugArr[1]}</h1>
{/if}
