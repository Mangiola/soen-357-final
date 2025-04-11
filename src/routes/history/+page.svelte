<script>
	import Box from "$lib/components/Box.svelte";
	import Button from "$lib/components/Button.svelte";
</script>

<div class="flex w-full flex-col items-center justify-center pb-24">
    <Box shape="v" color="amber" title="this month" classes="md:w-3/4 items-center">
        <img src="/images/stat3.png" alt="graph" class="hidden md:block p-5">
        <img src="/images/stat1.png" alt="graph" class="block md:hidden p-5 w-160">
        <img src="/images/stat2.png" alt="graph" class="block md:hidden p-5 w-160">
    </Box>
    <Box color="pink" title="last few days" classes="md:w-3/4">
        <div class="stats flex w-full">
            <div class="hidden lg:block flex-grow bg-pink-100 p-2 mx-3 my-2 rounded-md">
                <h3>sunday</h3>
                <p>3/3 meals</p>
                <p>1980 calories</p>
                <p>102g protein</p>
            </div>
            <div class="flex-grow bg-pink-100 p-2 mx-3 my-2 rounded-md">
                <h3>monday</h3>
                <p>3/3 meals</p>
                <p>1810 calories</p>
                <p>98g protein</p>
            </div>
            <div class="flex-grow bg-pink-100 p-2 mx-3 my-2 rounded-md">
                <h3>tuesday</h3>
                <p>2/3 meals</p>
                <p>1302 calories</p>
                <p>77g protein</p>
            </div>
            <div class="flex-grow bg-pink-100 p-2 mx-3 my-2 rounded-md">
                <h3>wednesday</h3>
                <p>3/3 meals</p>
                <p>1950 calories</p>
                <p>103g protein</p>
            </div>
        </div>
    </Box>

</div>
<Button title="Edit Goals"></Button>
