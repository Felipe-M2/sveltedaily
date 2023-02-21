<script>
	import Navbar from "./components/navbar.svelte";
	import Menu from "./components/menu.svelte";
</script>

<svelte:head>
	<title>svelteDaily</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<header>
		<Navbar/>
	</header>

	<main>
		<Menu/>
	</main>
</section>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');

	*{
        margin: 0;
        padding: 0;
        list-style: none;
        box-sizing: border-box;
		font-family: 'Inter', sans-serif;
    }
</style>