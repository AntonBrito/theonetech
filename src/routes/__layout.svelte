<script>
	import Footer from '../components/Footer.svelte';
	import '../app.css';
	import Header from '../components/Header.svelte';
	import Nav from '../components/Nav.svelte';
</script>

<div class=" flex flex-col bg-gradient-to-b from-blue-300 to to-blue-500 h-screen">
	<Header />
	<Nav />
	<div class="mb-auto">
		<slot />
	</div>
	<Footer />
</div>
