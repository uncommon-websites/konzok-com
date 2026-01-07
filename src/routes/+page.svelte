<script lang="ts">
	import "../app.css";
</script>

<div class="min-h-screen flex flex-col justify-between p-6 sm:p-8 md:p-12 lg:p-16 font-sans text-[#111] bg-white selection:bg-gray-200">
	<!-- Spacer for vertical centering alignment, but biased towards top/center -->
	<div class="flex-1 flex flex-col justify-center max-w-[900px]">
		
		<!-- Headline -->
		<h1 class="text-2xl sm:text-3xl md:text-[2rem] leading-[1.3] font-bold tracking-tight mb-10 text-black">
			Thilo is <span class="inline-block bg-[#f2f2f2] px-2 py-0.5 rounded-[5px] font-bold align-baseline">Uncommon</span> Founder, Partner and <span class="inline-block bg-[#f2f2f2] px-2 py-0.5 rounded-[5px] font-bold align-baseline">Sequoia</span> Arc Advisor.
		</h1>

		<!-- Body Text -->
		<div class="text-lg sm:text-xl md:text-[1.35rem] leading-[1.6] text-[#888888] font-normal tracking-tight">
			He invested, advised or designed 
			{#each ["Mercor", "Delphi", "Squint", "Dash0", "CrewAI", "GradientLabs", "Build", "Fleet", "Medra", "nsave", "Ironbridge", "DiligenceSquared", "Lemni", "Morphic", "Compile", "Lapel", "Orbit", "Sensmore", "Nolla", "Luo", "Hero", "Popcorn", "Partykit", "Guided Energy", "Commerce Systems", "Claim", "Structify", "Snaptrude", "Superlinked", "Tilebox", "Amperecloud", "Equipme", "Documenso"] as company, i}
				<span class="inline-block bg-[#f4f4f5] text-black px-1.5 py-0.5 rounded-[4px] align-baseline">{company}</span>{#if i < 32}<span>, </span>{/if}
			{/each}
			and <span class="inline-block bg-[#f4f4f5] text-black px-1.5 py-0.5 rounded-[4px] align-baseline">Era</span>, founded <span class="inline-block bg-[#f4f4f5] text-black px-1.5 py-0.5 rounded-[4px] align-baseline">Home</span>, worked at <span class="inline-block bg-[#f4f4f5] text-black px-1.5 py-0.5 rounded-[4px] align-baseline">Airbnb</span> in 2011 and studied architecture – DM anytime on <span class="inline-block bg-[#f4f4f5] text-black px-1.5 py-0.5 rounded-[4px] align-baseline">X</span> or <span class="inline-block bg-[#f4f4f5] text-black px-1.5 py-0.5 rounded-[4px] align-baseline">LinkedIn</span>.
		</div>

		<!-- CTA -->
		<p class="mt-10 text-lg sm:text-xl md:text-[1.35rem] text-[#888888] font-normal tracking-tight">
			How can we work together?
		</p>
	</div>

	<!-- Footer -->
	<div class="flex justify-between items-end mt-12 w-full">
		<div class="text-xl text-black font-light select-none">|</div>
		<button class="w-12 h-12 bg-[#f4f4f5] rounded-full flex items-center justify-center hover:bg-gray-200 transition-colors cursor-pointer" aria-label="Next">
			<svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-[#9ca3af]">
				<line x1="5" y1="12" x2="19" y2="12"></line>
				<polyline points="12 5 19 12 12 19"></polyline>
			</svg>
		</button>
	</div>
</div>

