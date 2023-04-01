<script>
	import { goto } from '$app/navigation';

	const handleOrder = () => {
		console.log('Placing order successfully!');
		goto('/products', { replaceState: true });
	};
</script>

<h1>Welcome home!</h1>

<div>
	<button on:click={handleOrder}>Place order</button>
</div>
