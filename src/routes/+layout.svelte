<script lang="ts">
	import ThemeInitializer from '$lib/components/ThemeInitializer.svelte';
	import '../app.css';
	import MainHeader from '$lib/components/MainHeader.svelte';
</script>

<ThemeInitializer>
	<MainHeader />
	<main>
		<slot />
	</main>
</ThemeInitializer>
