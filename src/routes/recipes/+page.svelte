<script>
	import Box from "$lib/components/Box.svelte";
	import Button from "$lib/components/Button.svelte";
</script>

<div class="xl:px-64 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 lg:gap-8 w-full h-full p-10 pt-2">
    
    <Box shape="v" color="gray" classes="lg:col-span-3 sm:col-span-2">
        <input class="bg-gray-100 w-full h-full p-3 text-xl" placeholder="search recipes..."/>
    </Box>
    
    <Box shape="v" color="teal">
        <img class="w-full" src="/images/suggest1.png" alt="yogurt">
        <div class="recipe h-43 w-full px-4 pb-4 text-right">
            <h3>ingredients</h3>
            <p>paprika, garlic powder, cayenne powder, breadcrumbs, unsalted butter, 1 pound skin-on salmon</p>
            <h3 class="mt-4">instructions</h3>
            <p>Preheat the oven to 425 degrees</p>
            <p>Line a baking sheet with foil</p>
            <p>Mix the panko with the parsley, butter, 1/4 teaspoon kosher salt and a few grinds of black pepper</p>
            <p>...</p>
        </div>
    </Box>
    <Box shape="v" color="amber">
        <img class="w-full" src="/images/suggest_7.png" alt="yogurt">
        <div class="recipe h-43 w-full px-4 pb-4 text-right">
            <h3>ingredients</h3>
            <p>filet mignon, butter, salt, pepper</p>
            <h3 class="mt-4">instructions</h3>
            <p>Preheat iron skillet over stove</p>
            <p>Melt butter in skillet</p>
            <p>Sear each side</p>
            <p>...</p>
        </div>
    </Box>
    <Box shape="v" color="pink">
        <img class="w-full" src="/images/suggest_6.png" alt="yogurt">
        <div class="recipe h-43 w-full px-4 pb-4 text-right">
            <h3>ingredients</h3>
            <p>macaroni, basil, tomato sauce, salt</p>
            <h3 class="mt-4">instructions</h3>
            <p>Bring water to boil in a pot</p>
            <p>Add salt to pot (to taste)</p>
            <p>Place pasta in pot, cook for six minutes</p>
            <p>...</p>
        </div>
    </Box>
    <Box shape="v" color="amber">
        <img class="w-full" src="/images/suggest_8.png" alt="yogurt">
        <div class="recipe h-43 w-full px-4 pb-4 text-right">
            <h3>ingredients</h3>
            <p>chicken breast, seasoning, salt</p>
            <h3 class="mt-4">instructions</h3>
            <p>Defrost chicken breasts in fridge overnight</p>
            <p>Preheat oven to 425F</p>
            <p>Place chicken in pan, lather seasoning</p>
            <p>...</p>
        </div>
    </Box>
    <Box shape="v" color="pink">
        <img class="w-full" src="/images/suggest_9.png" alt="yogurt">
        <div class="recipe h-43 w-full px-4 pb-4 text-right">
            <h3>ingredients</h3>
            <p>small potatoes, salt, butter, milk</p>
            <h3 class="mt-4">instructions</h3>
            <p>Bring water to boil in a pot</p>
            <p>Peel potatoes</p>
            <p>Place potatoes in the pot</p>
            <p>...</p>
        </div>
    </Box>
    <Box shape="v" color="teal">
        <img class="w-full" src="/images/suggest_10.png" alt="yogurt">
        <div class="recipe h-43 w-full px-4 pb-4 text-right">
            <h3>ingredients</h3>
            <p>macaroni, basil, tomato sauce, salt</p>
            <h3 class="mt-4">instructions</h3>
            <p>Bring water to boil in a pot</p>
            <p>Add salt to pot (to taste)</p>
            <p>Place pasta in pot, cook for six minutes</p>
            <p>...</p>
        </div>
    </Box>
    <Box shape="v" color="teal">
        <img class="w-full" src="/images/suggest2.png" alt="yogurt">
        <div class="recipe h-43 w-full px-4 pb-4 text-right">
            <h3>ingredients</h3>
            <p>ground oats, flour, blueberries</p>
            <h3 class="mt-4">instructions</h3>
            <p>Preheat oven to 400F</p>
            <p>Place layer of oats in a deep pan</p>
            <p>...</p>
        </div>
    </Box>
    <Box shape="v" color="amber">
        <img class="w-full" src="/images/suggest3.png" alt="yogurt">
        <div class="recipe h-43 w-full px-4 pb-4 text-right">
            <h3>ingredients</h3>
            <p>spinach, garlic, olive oil</p>
            <h3 class="mt-4">instructions</h3>
            <p>Simmer olive oil in pan</p>
            <p>Wash spinach in bowl</p>
            <p>Place spinach in pan</p>
            <p>...</p>
        </div>
    </Box>
    <Box shape="v" color="pink">
        <img class="w-full" src="/images/suggest4.png" alt="yogurt">
        <div class="recipe h-43 w-full px-4 pb-4 text-right">
            <h3>ingredients</h3>
            <p>dried banana, dried apple, almonds, cashews</p>
            <h3 class="mt-4">instructions</h3>
            <p>Mix all ingredients</p>
        </div>
    </Box>
</div>

<style>
    .recipe {
        overflow: scroll;
    }
    h3 {
        font-weight: 700;
    }
</style>