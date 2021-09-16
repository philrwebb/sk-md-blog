# About

<script>
    import Box from './box.svelte';
    let count = 10
</script>

{count}

<button on:click={() => count +=1}>Increment {count}</button>

<Box />