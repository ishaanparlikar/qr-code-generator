<script>
	import '../app.css';
	import Navbar from '../components/Navbar.svelte';
</script>

<template>
	<div class="container mx-auto">
		<Navbar />
		<slot />
	</div>
</template>
