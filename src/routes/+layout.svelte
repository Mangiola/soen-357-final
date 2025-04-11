<script>
	import '../app.css';
	import { page } from '$app/state';

	let { children } = $props();
</script>

<div class="w-full h-screen flex flex-col">
	<div class="flex justify-center md:justify-between items-center h-24 px-5">
		<h1 class="hidden md:block font-extrabold text-5xl ml-5">fuüd</h1>
		<nav class="flex justify-between">
			<a href="/" aria-current={page.url.pathname === '/'} class="font-light p-3 m-2">
				<div class="flex flex-col justify-center items-center w-12">
					<img src={page.url.pathname === '/' ? "/home.svg" : "/home_off.svg"} alt="" height="30px" width="30px"/>
					home
				</div>
			</a>
			<a href="/routine" aria-current={page.url.pathname === '/routine/'} class="font-light p-3 m-2">
				<div class="flex flex-col justify-center items-center w-12">
					<img src={page.url.pathname === '/routine' ? "/routine.svg" : "/routine_off.svg"} alt="" height="30px" width="30px"/>
					routine
				</div>
			</a>
			<a href="/history" aria-current={page.url.pathname === '/history/'} class="font-light p-3 m-2">
				<div class="flex flex-col justify-center items-center w-12">
					<img src={page.url.pathname === '/history' ? "/history.svg" : "/history_off.svg"} alt="" height="30px" width="30px"/>
					history
				</div>
			</a>
			<a href="/recipes" aria-current={page.url.pathname === '/recipes/'} class="font-light p-3 m-2">
				<div class="flex flex-col justify-center items-center w-12">
					<img src={page.url.pathname === '/recipes' ? "/recipes.svg" : "/recipes_off.svg"} alt="" height="30px" width="30px"/>
					recipes
				</div>
			</a>
		</nav>
	</div>
	<div class="h-full flex flex-col items-center md:justify-center w-full">
		{@render children()}
	</div>
</div>

<style>
	a[aria-current="true"] {
		font-weight: 600;
		border: 2px solid black;
		border-radius: 10px;
	}
	a:hover {
		font-weight: 600;
	}
</style>

