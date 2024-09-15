<script>
	export let productId = 100;
</script>

<h1>Product list</h1>

<h2><a href="/products/1" class="underline">Product 1</a></h2>
<h2><a href="/products/2" class="underline">Product 2</a></h2>
<h2><a href="/products/3" class="underline">Product 3</a></h2>
<h2><a href={`/products/${productId}`} class="underline">Product 100</a></h2>

<a href="/">Home</a>
