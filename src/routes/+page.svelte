<script>
  // components importing
	import Nav from './components/nav.svelte';

  // src and links
	import HeadingImage from "$lib/assets/hero-Illustration.png"

  // logic and functions
</script>

<body>
	<header><Nav /></header>
	<main>
		<h1>Welcome to Fibres</h1>
		<p>Website Prototype of Fibre: Online Portfolio Maker by Matthew</p>
		<p>This is only a prototype for me to discover svelte and practice layouting</p>
		<img src={HeadingImage} alt="what the hell">
	</main>
	<footer></footer>
</body>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap');
	* {
		padding: 0;
		margin: 0;
		font-family: 'Inter', sans-serif;
		box-sizing: border-box;
		font-size: 14px;
	}

	/* a {
		text-decoration: none;
	} */

	body {
		font-family: 'Inter', sans-serif;
	}
</style>
