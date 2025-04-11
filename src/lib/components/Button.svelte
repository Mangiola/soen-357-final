<script>
	let { title } = $props();
</script>

<button class="border-5 px-12 py-2 uppercase font-bold bg-purple-200">{title}</button>

<style>
    button {
        box-shadow: 8px 8px;
    }
    button:hover {
        background-color: rgb(225, 201, 234);
        cursor: pointer;
    }
</style>