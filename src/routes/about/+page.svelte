<svelte:head>
	<title>About DDEV Testing</title>
	<meta name="description" content="Test page for DDEV to find at /about" />
</svelte:head>

<div class="text-column">
	<h1>Test page for DDEV to find at /about</h1>

	<p>
		This project is just for automated testing of DDEV.
	</p>

	<pre>npx sv create</pre>

	<p>
		The page you're looking at is purely static HTML, with no client-side interactivity needed.
		Because of that, we don't need to load any JavaScript. Try viewing the page's source, or opening
		the devtools network panel and reloading.
	</p>

	<p>
		The <a href="/sverdle">Sverdle</a> page illustrates SvelteKit's data loading and form handling. Try
		using it with JavaScript disabled!
	</p>
</div>
