<script>
	export let load
	import Button from './components/button.svelte';

	import Shapes from './components/shapes.svelte';
</script>
<section class="bg-neutral-900 min-h-[750px] h-[100vh] grid lg:mt-[-164px] mt-[-130px] items-center ">
<div class="about max-w-[1730px] px-2 3xs:px-8 pb-8 max-lg:flex-col h-max  flex lg:justify-evenly mx-auto">
	<div class="left lg:flex flex-col justify-around">
		<h1 class=" text-5xl md:text-7xl 2md:text-8xl xl:text-9xl text-neutral-300 hover:text-[#c33838] font-extrabold">About Me</h1>
		<div class="flex md:gap-2 text-neutral-400 hover:text-neutral-500 flex-col md:p-4 py-1">
			<p class=" 2xs:text-xl md:text-2xl xl:text-3xl font-bold hover:text-[#c5992f]">
				Hi 👋, I'm <span class=" text-xl 2xs:text-2xl md:text-3xl xl:text-4xl">G.Meghashyam</span>.
			</p>
			<div class="2xs:text-xl md:text-2xl xl:text-3xl font-bold">
				<p class="my-1 md:mb-2 hover:text-[#36a45e]">A Harmonious blend of creativity and utility 🚀✨</p>
				<p class="hover:text-[#6377b5]">~ “A creative mess is better than tidy idleness."</p>
			</div>
		</div>
		<div class="flex gap-1">
			<a href="mailto:gurrammeghashyam@gmail.com"><Button /></a>
			<button class="flex mt-2 md:hidden items-center bg-neutral-800 p-2 px-5 rounded-full"
			><a href="mailto:gurrammeghashyam@gmail.com" class="flex items-center"><span class="font-bold text-neutral-300 xs:tracking-[0.25em] text-xs leading-[18px] uppercase text-centerd">Contact Me</span>
				<svg
					width="13px"
					height="10px"
					stroke-width="2"
					class=" stroke-neutral-300"
					viewBox="0 0 13 10"
				>
					<!-- <path d="M1,5 L11,5" /> -->
					<polyline points="8 1 12 5 8 9" />
				</svg></a></button
		>
			<a href="https://rxresu.me/meghashyam1218/resume" target="_blank" class="flex gap-1 mt-2 max-w-[210px] hover:border-neutral-800 border-2 border-neutral-900 transition-all ease-in rounded-full items-center p-4"
				><p class="font-bold text-neutral-400 xs:tracking-[0.25em] text-xs md:text-sm leading-[18px] uppercase text-centerd">Get Resume</p><img alt="dowload" src="/download.svg"/>
				</a
			></div>
		
	</div>
	<Shapes load={load} />
</div>

</section>
