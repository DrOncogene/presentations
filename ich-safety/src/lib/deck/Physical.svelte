<script lang="ts">
	import hosp1 from '$lib/assets/hosp-1.png';
	import hosp2 from '$lib/assets/hosp-2.gif';
	import hosp3 from '$lib/assets/hosp-3.jpeg';
	import hosp4 from '$lib/assets/hosp-4.jpg';
</script>

<section class="text-left">
	<section>
		<h3 class="prose">PHYSICAL SAFETY</h3>
		<p class="prose prose-2xl">Components of physical safety:</p>
		<ul class="prose prose-xl prose-li:text-white">
			<li>Building design</li>
			<li>Security personnel</li>
			<li>Accessibility</li>
			<li>Fire safety</li>
		</ul>
	</section>
	<section>
		<h3 class="prose">PHYSICAL SAFETY: Design</h3>
		<img class="aspect-[2/1] h-[500px]" src={hosp1} alt="" />
	</section>
	<section>
		<h3 class="prose">PHYSICAL SAFETY: Personnel</h3>
		<p class="prose prose-2xl">Personnel should be:</p>
		<ul class="prose prose-xl prose-li:text-white">
			<li>Well trained</li>
			<li>Well paid</li>
			<li>Well equipped</li>
		</ul>
	</section>
	<section>
		<h3 class="prose">PHYSICAL SAFETY: Accessibility</h3>
		<div class="flex items-start justify-between">
			<div>
				<ul class="prose prose-xl prose-li:text-white">
					<li>
						<p class="prose prose-2xl">Same-floor and between-floor access:</p>
						<ul class="prose prose-xl prose-li:text-white">
							<li>Spacious corridors</li>
							<li>Ramps/Elevators</li>
						</ul>
					</li>
					<li class="fragment fade-right">Ensures safe movement and transport</li>
				</ul>
			</div>
			<div>
				<img class="h-[400px] w-[500px]" src={hosp2} alt="" />
			</div>
		</div>
	</section>
	<section>
		<h3 class="prose">PHYSICAL SAFETY: Fire</h3>
		<div class="flex items-start justify-between">
			<div>
				<p class="prose prose-2xl">
					Fire prevention entails measures prevent and curb fire incidents
				</p>
				<ul class="prose prose-xl prose-li:text-white">
					<li>Emergency exits on each floor</li>
					<li>Fire extinguishers</li>
					<li>Fire hose</li>
					<li>Adequate water supply</li>
				</ul>
			</div>
			<div class="flex flex-col">
				<img class="block h-[200px] w-[400px]" src={hosp3} alt="" />
				<img class="block h-[200px] w-[400px]" src={hosp4} alt="" />
			</div>
		</div>
	</section>
</section>
