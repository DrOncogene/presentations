<script lang="ts">
	import hosp5 from '$lib/assets/hosp-5.jpg';
	import hosp6 from '$lib/assets/hosp-6.jpg';
	import hosp7 from '$lib/assets/hosp-7.jpg';
	import hosp8 from '$lib/assets/hosp-8.webp';
</script>

<section class="text-left">
	<section>
		<h3 class="prose">DATA SAFETY</h3>
		<div class="grid grid-cols-2 gap-10">
			<div>
				<p class="fragment fade-up prose prose-2xl">Privacy is paramount</p>
				<ul class="prose prose-xl prose-li:text-white">
					<li class="fragment fade-right">Auditory</li>
					<li class="fragment fade-right">Visual</li>
					<li class="fragment fade-right">Written</li>
				</ul>
			</div>
			<div>
				<p class="fragment fade-up prose prose-2xl">Data loss can be caused by:</p>
				<ul class="prose prose-xl prose-li:text-white">
					<li class="fragment fade-right">Fire 🔥</li>
					<li class="fragment fade-right">Water 💦</li>
					<li class="fragment fade-right">Spontaneous degradation</li>
					<li class="fragment fade-right">Theft</li>
				</ul>
			</div>
		</div>
		<p class=" fragment prose prose-xl">
			Many of these pitfalls can be avoided by switching to <i>Electronic Medical Records</i>
		</p>
	</section>
	<section>
		<h3 class="prose">DATA SAFETY</h3>
		<div class="grid grid-cols-2 gap-10">
			<div>
				<p class="prose prose-2xl">Measures to improve safety include:</p>
				<ul class="prose prose-xl prose-li:text-white">
					<li class="fragment fade-right" data-fragment-index="1">
						Reduce the number of <i>leakage points</i>
					</li>
					<li class="fragment fade-right" data-fragment-index="2">Regular data audits</li>
					<li class="fragment fade-right" data-fragment-index="3">
						Using safer file storage mechanisms
					</li>
					<li class="fragment fade-right" data-fragment-index="7">Regular data backups</li>
					<li class="fragment fade-right" data-fragment-index="8"><i>And more...</i></li>
				</ul>
			</div>
			<div class="grid grid-cols-2 grid-rows-2 gap-2">
				<img class="fragment h-[200px] w-[300px]" src={hosp7} alt="" data-fragment-index="4" />
				<img class="fragment h-[200px] w-[300px]" src={hosp5} alt="" data-fragment-index="5" />
				<img class="fragment h-[200px] w-[300px]" src={hosp6} alt="" data-fragment-index="6" />
				<!-- <img class="h-[200px] w-[300px]" src={hosp8} alt="" data-fragment-index="3" /> -->
			</div>
		</div>
	</section>
</section>
