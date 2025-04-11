<script>
	import Box from "$lib/components/Box.svelte";

</script>

<div class="flex w-full flex-col md:flex-row items-center justify-center pb-24">
    <div class="flex flex-col w-full md:w-100 md:p-10">
        <Box shape="v" color="teal" title="next meal">
            <img src="/images/salmon.png" alt="baked salmon" class="px-4 pt-4">
            <h3 class="text-xl py-1">baked salmon</h3>
            <table class="mb-4">
                <tbody>
                    <tr>
                        <td>prep time</td>
                        <td>10min</td>
                    </tr>
                    <tr>
                        <td>cook time</td>
                        <td>30min</td>
                    </tr>
                    <tr>
                        <td>start cooking</td>
                        <td>17:30</td>
                    </tr>
                    <tr>
                        <td>calories</td>
                        <td>468</td>
                    </tr>
                    <tr>
                        <td>protein</td>
                        <td>50g</td>
                    </tr>
                    <tr>
                        <td>carbohydrates</td>
                        <td>0g</td>
                    </tr>
                </tbody>
            </table>
        </Box>
    </div>
    <div class="flex flex-col w-full md:w-2/3 md:p-10">
        <Box shape="h" color="amber" title="weekly stats">
            <div class="stats flex w-full">
                <div class="hidden lg:block flex-grow bg-amber-100 p-2 mx-3 my-2 rounded-md">
                    <h3>sunday</h3>
                    <p>3/3 meals</p>
                    <p>1980 calories</p>
                    <p>102g protein</p>
                </div>
                <div class="flex-grow bg-amber-100 p-2 mx-3 my-2 rounded-md">
                    <h3>monday</h3>
                    <p>3/3 meals</p>
                    <p>1810 calories</p>
                    <p>98g protein</p>
                </div>
                <div class="flex-grow bg-amber-100 p-2 mx-3 my-2 rounded-md">
                    <h3>tuesday</h3>
                    <p>2/3 meals</p>
                    <p>1302 calories</p>
                    <p>77g protein</p>
                </div>
                <div class="flex-grow bg-amber-100 p-2 mx-3 my-2 rounded-md">
                    <h3>wednesday</h3>
                    <p>3/3 meals</p>
                    <p>1950 calories</p>
                    <p>103g protein</p>
                </div>
            </div>
        </Box>
        
        <Box shape="h" color="pink" title="suggestions">
            <div class="flex flex-col md:flex-row">
                <div class="px-10">
                    <img src="/images/suggest2.png" alt="spinach" width="250px">
                    <img src="/images/suggest3.png" alt="fruit mix" width="250px">
                    <img src="/images/suggest4.png" alt="yogurt" width="250px">
                </div>
                <div class="px-10 h-full">
                    <img src="/images/suggest5.png" alt="blueberry bars" width="250px">
                    <img src="/images/suggest_6.png" alt="yogurt" width="250px">
                    <img src="/images/suggest_7.png" alt="fruit mix" width="250px">
                </div>
                <div class="hidden xl:block px-10">
                    <img src="/images/suggest_8.png" alt="spinach" width="250px">
                    <img src="/images/suggest_9.png" alt="blueberry bars" width="250px">
                    <img src="/images/suggest_10.png" alt="yogurt" width="250px">
                </div>
            </div>
        </Box>
    </div>
</div>

<style>
    table td {
        padding-left: 4px;
        padding-right: 4px;
        width: 40%;
        font-weight: 600;
    }
    table {
        width: 100%;
    }
    table td:first-child {
        text-align: right;
        font-weight: 300;
    }

    .stats h3 {
        font-weight: 600;
    }
    .stats p {
        font-size: 12px;
    }
</style>