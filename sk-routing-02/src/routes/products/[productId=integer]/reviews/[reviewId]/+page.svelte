<script>
	import { page } from '$app/stores';

	// const reviewId = $page.params.reviewId;
	// const productId = $page.params.productId;

	const { productId, reviewId } = $page.params;

	// console.log($page.params);
</script>

<h1>Review about product {productId}</h1>
<h3>Content for Review {reviewId}</h3>
