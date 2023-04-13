<script lang="ts">
	import '../layout.css';
	import Navbar from '../components/navbar/navbar.svelte';
	import Footer from '../components/footer/footer.svelte';
</script>

<div>
	<Navbar />
	<div class="min-h-screen">
		<slot />
	</div>
	<Footer />
</div>

<style>
</style>
