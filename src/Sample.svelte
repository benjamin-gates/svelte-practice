<script>
    let message = "today, we will be learning Svelte!";
    export let count;
    function handleCount(){
        count += 1;
    }
</script>
<div>
    <h1>Here is your Message!</h1>
<p>{message}</p>
<button on:click={handleCount}>Click Me! {count}</button>
</div>

<style>
    p {
        font-weight: bold;
        font-style: italic;
    }
    button {
        border-radius: 50%;
        border-color: green;
    }
</style>
