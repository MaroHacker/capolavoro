<script>
	import Scale from 'lucide-svelte/icons/scale';

	import { page } from '$app/stores';

	let currentUrl = $page.url.pathname;

	$: isHome = currentUrl === '/';
	$: isAbout = currentUrl === '/about';

	function handleLinkClick(url) {
		currentUrl = url;
	}
</script>

<div class="flex flex-col items-center justify-center px-6 py-4">
	<div class="flex items-center space-x-6">
		<a
			href="/"
			class="{isHome
				? 'text-2xl font-bold text-primary'
				: ''} transition-colors duration-300 hover:text-primary dark:hover:text-gray-300"
			on:click={() => handleLinkClick('/')}>Home</a
		>
		<a
			href="/about"
			class="{isAbout
				? 'text-2xl font-bold text-primary'
				: ''} transition-colors duration-300 hover:text-primary dark:hover:text-gray-300"
			on:click={() => handleLinkClick('/about')}>About</a
		>
	</div>
	<Scale class="h-12 w-12" />
</div>
