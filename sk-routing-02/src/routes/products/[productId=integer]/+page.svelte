<script>
	import { page } from '$app/stores';

	const productId = $page.params.productId;
</script>

<h1>Product {productId}</h1>
<h3>Description for product {productId}</h3>

<p><a href="{productId}/reviews/1">Review 1</a></p>
<p><a href="{productId}/reviews/2">Review 2</a></p>
<p><a href="{productId}/reviews/3">Review 3</a></p>
