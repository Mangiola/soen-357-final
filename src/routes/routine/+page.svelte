<script>
	import Box from "$lib/components/Box.svelte";
	import Button from "$lib/components/Button.svelte";

</script>
<div class="flex w-full flex-col md:flex-row items-center justify-center pb-10">
    <Box color="teal" title="today" shape="v" classes="md:w-70">
        <h3>breakfast</h3>
        <div class="group">
            <img class="w-full" src="/images/suggest5.png" alt="yogurt">
            <p>
                <span class="label">time</span>6:30
                <span class="label">calories</span>80
            </p>
        </div>
        <h3>lunch</h3>
        <div class="group">
            <img class="w-full" src="/images/suggest_6.png" alt="yogurt">
            <p>
                <span class="label">time</span>12:30
                <span class="label">calories</span>200
            </p>
        </div>
        <h3>dinner</h3>
        <div class="group">
            <img class="w-full" src="/images/suggest1.png" alt="salmon">
            <p>
                <span class="label">time</span>18:30
                <span class="label">calories</span>80
            </p>
            <img class="w-full" src="/images/suggest3.png" alt="spinach">
            <p>
                <span class="label">time</span>18:30
                <span class="label">calories</span>80
            </p>
        </div>
    </Box>

    <Box color="amber" title="tomorrow" shape="v" classes="md:w-70">
        <h3>breakfast</h3>
        <div class="group">
            <img class="w-full" src="/images/suggest2.png" alt="yogurt">
            <p>
                <span class="label">time</span>6:30
                <span class="label">calories</span>80
            </p>
        </div>
        <h3>lunch</h3>
        <div class="group">
            <img class="w-full" src="/images/suggest_7.png" alt="yogurt">
            <p>
                <span class="label">time</span>6:30
                <span class="label">calories</span>80
            </p>
        </div>
        <h3>dinner</h3>
        <div class="group">
            <img class="w-full" src="/images/suggest_8.png" alt="salmon">
            <p>
                <span class="label">time</span>6:30
                <span class="label">calories</span>80
            </p>
            <img class="w-full" src="/images/suggest_9.png" alt="spinach">
            <p>
                <span class="label">time</span>6:30
                <span class="label">calories</span>80
            </p>
        </div>
    </Box>

    <Box color="pink" title="in 2 days" shape="v" classes="md:w-70">
        <h3>breakfast</h3>
        <div class="group">
            <img class="w-full" src="/images/suggest4.png" alt="yogurt">
            <p>
                <span class="label">time</span>6:30
                <span class="label">calories</span>80
            </p>
        </div>
        <h3>lunch</h3>
        <div class="group">
            <img class="w-full" src="/images/suggest_6.png" alt="yogurt">
            <p>
                <span class="label">time</span>6:30
                <span class="label">calories</span>80
            </p>
        </div>
        <h3>dinner</h3>
        <div class="group">
            <img class="w-full" src="/images/suggest_10.png" alt="salmon">
            <p>
                <span class="label">time</span>6:30
                <span class="label">calories</span>80
            </p>
            <img class="w-full" src="/images/suggest3.png" alt="spinach">
            <p>
                <span class="label">time</span>6:30
                <span class="label">calories</span>80
            </p>
        </div>
    </Box>
</div>
<Button title="Edit Routine"></Button>

<style>
    h3 {
        font-weight: 300;
        font-size: 24px;
        width: 100%;
        text-align: left;
        padding-left: 15px;
        padding-top: 10px;
    }
    .group p {
        font-size: 14px;
    }
    .group .label {
        font-weight: 800;
        margin-right: 7px;
        margin-left: 15px;
    }
    .group {
        padding-bottom: 20px;
        text-align: left;
    }
    .group img {
        max-width: 300px;
    }
    img:hover {
        filter: brightness(120%);
    }
</style>