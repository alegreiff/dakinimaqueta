<script lang="ts">
	import '@picocss/pico/css/pico.min.css';
	import MenuPrincipal from '$lib/componentes/MenuPrincipal.svelte';
</script>

<main class="container">
	<MenuPrincipal />
	<slot />
</main>
