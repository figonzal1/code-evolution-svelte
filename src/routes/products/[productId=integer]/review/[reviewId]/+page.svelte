<script>
	import { page } from '$app/stores';

    const { productId, reviewId} = $page.params;
</script>

<h1>Review id: {reviewId} of product {productId}</h1>