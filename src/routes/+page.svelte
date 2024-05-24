<script>
	import { slide } from 'svelte/transition';
</script>

<div
	transition:slide={{ y: -100, duration: 300 }}
	class="flex h-[calc(100vh-64px-32px)] flex-col items-center justify-center"
>
	<h1
		class="text-center text-xl font-semibold leading-normal md:text-3xl lg:text-6xl lg:leading-normal"
	>
		Benvenuti nel mio sito personale!<br /> Sono uno studente che ambisce ad ampliare le proprie<br
		/>
		conoscenze nell'ambito
		<span class="bg-gradient-to-r from-primary to-blue-600 bg-clip-text text-transparent">
			storico e giuridico
		</span>
	</h1>
</div>
