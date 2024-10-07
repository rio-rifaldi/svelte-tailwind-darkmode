<script>
	 import { ModeWatcher } from "mode-watcher";
	import '$styles/app.css';
	import ThemeToggle from "$lib/components/ThemeToggle.svelte";
</script>

<svelte:head>
	<title>sveltekit darkmode + tailwindcss</title>
</svelte:head>

<ModeWatcher />
<div class="p-5">
	<ThemeToggle />
</div>
<slot />

