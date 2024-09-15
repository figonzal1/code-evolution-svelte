<script>
	const greetings = {
		en: 'Hello',
		es: 'Hola'
	};

	import { page } from '$app/stores';

	const { lang = "en" } = $page.params;

	const greeting = greetings[lang];
</script>

<h1>{greeting}</h1>
