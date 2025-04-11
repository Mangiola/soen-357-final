<script>
	let { children, shape, color, title, classes } = $props();
</script>

<div class={classes+" m-3"}>
    <h2 class="text-3xl">{title}</h2>
    <div class={"flex items-center justify-between bg-"+color+"-200 border-5 my-shadow flex-col md:flex-row"+(shape=="v"?"md:flex-col":"")}>
        {@render children()}
    </div>
</div>

<div class="bg-pink-200 bg-amber-200 bg-teal-200 bg-gray-200 hidden"></div>

<style>
    .my-shadow {
        box-shadow: 8px 8px;
    }
    .bg-teal-200, .bg-pink-200, .bg-amber-200 {
        /* TailwindCSS needs this empty ruleset for caching purposes */
    }
</style>