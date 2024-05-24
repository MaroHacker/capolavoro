<script>
	import { slide } from 'svelte/transition';
</script>

<div transition:slide={{ y: -100, duration: 300 }} class="lg:mx-auto lg:w-3/6">
	<div class="mx-auto max-w-4xl p-4">
		<h1 class="mb-16 mt-7 text-6xl font-extrabold tracking-wider text-primary">Chi Sono</h1>
		<p class="my-16 text-xl font-medium leading-7 tracking-wider">
			Ciao! Mi chiamo Davide Marino sono nato l' 01/05/2005 e sto concludendo il mio ultimo anno
			scolastico, provengo da Chieti (Abruzzo) ed il mio grande sogno è di diventare giudice.
		</p>
		<h2 class="my-8 text-4xl font-extrabold tracking-wider text-secondary">
			Da dove nasce quest passione
		</h2>

		<div class="text-lg font-normal">
			La mia passione per questa disciplina deriva dalle azione e dagli ideali irremovibili di
			grandissime figure come:
			<a
				href="https://it.wikipedia.org/wiki/Giovanni_Falcone"
				target="_blank"
				class="italic text-primary no-underline">Falcone Giovanni</a
			>,
			<a
				href="https://it.wikipedia.org/wiki/Paolo_Borsellino"
				target="_blank"
				class="italic text-primary no-underline">Borsellino Paolo</a
			>
			o
			<a
				href="https://it.wikipedia.org/wiki/Nicola_Gratteri"
				target="_blank"
				class="italic text-primary no-underline">Gratteri Nicola</a
			>
			il mio obiettivo sarà di replicare la loro grandezza lasciando il segno e rimanendo costante con
			i miei ideali per cercare di migliorare la nostra nazione.
		</div>

		<h2 class="my-8 text-4xl font-extrabold tracking-wider text-secondary">Competenze</h2>

		<div class="text-lg font-normal">
			Le mie attuali competenze sono irrilevanti nell'ambito in questione, ma durante gli anni,
			tramite la lettura di saggi, racconti ed esperienze ho sviluppato forti capacita' di giudizio
			e criticita' delle situazioni o persone
		</div>
	</div>
</div>
