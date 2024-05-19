<script lang="ts">
	import { onMount } from 'svelte';

	import Reveal from 'reveal.js';
	import Notes from 'reveal.js/plugin/notes/notes';
	import Search from 'reveal.js/plugin/search/search';
	import 'reveal.js/dist/reveal.css';
	import 'reveal.js/dist/theme/dracula.css';

	import Intro from './deck/Intro.svelte';
	import PhysicalSafety from './deck/Physical.svelte';
	import DataSafetey from './deck/Data.svelte';
	import ProcessSafety from './deck/Process.svelte';
	import Current from './deck/Current.svelte';
	import Recommendations from './deck/Recommendations.svelte';
	import Summary from './deck/Summary.svelte';

	onMount(() => {
		const deck = new Reveal({
			controls: true,
			progress: true,
			history: true,
			center: false,
			autoAnimate: true,
			autoAnimateEasing: 'ease',
			transition: 'convex',
			hash: true,
			navigationMode: 'linear'
		});

		deck.initialize({
			plugins: [Notes, Search]
		});
	});
</script>

<div class="reveal">
	<div class="slides text-left">
		<section>
			<h2 class="prose">BECOMING THE SAFEST HOSPITAL</h2>
			<div class="mt-20">
				<h4 class="prose">by</h4>
				<h4 class="prose">Nasir Abdulrasheed</h4>
			</div>
		</section>
		<section class="text-left">
			<h3 class="prose">OUTLINE</h3>
			<ul class="prose prose-2xl">
				<li class="fragment fade-right"><a href="#/2">Introduction</a></li>
				<li class="fragment fade-right"><a href="#/3">Physical Safety</a></li>
				<li class="fragment fade-right"><a href="#/4">Data Safety</a></li>
				<li class="fragment fade-right"><a href="#/5">Process Safety</a></li>
				<li class="fragment fade-right"><a href="#/6">Current Measures</a></li>
				<li class="fragment fade-right"><a href="#/7">Recommendations</a></li>
				<li class="fragment fade-right"><a href="#/8">Summary</a></li>
			</ul>
		</section>
		<Intro />
		<PhysicalSafety />
		<DataSafetey />
		<ProcessSafety />
		<Current />
		<Recommendations />
		<Summary />
		<section class="flex h-full w-full items-center justify-center">
			<h3 class="prose">ARIGATO 🙏🏽🙏🏽</h3>
			<h3 class="prose">THANKS FOR LISTENING</h3>
		</section>
	</div>
</div>
