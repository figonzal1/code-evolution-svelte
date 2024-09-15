<script>
	import '../app.css';
	import { goto } from '$app/navigation';

	function handleClick() {
		console.log('PLacing order', { replaceState: true });
		goto('/products');
	}
</script>

<h1 class="text-lg text-red-400 font-bold">Welcome to SvelteKit</h1>
<p>
	Visit <a class="underline text-blue-500" href="https://kit.svelte.dev">kit.svelte.dev</a> to read the
	documentation
</p>

<a href="/blog">Blog</a>
<a href="/products">Products</a>

<button on:click={handleClick}>Place order</button>
