<script>
    let count = 0;

    const increment = () => {
        count++;
    }

    const decrement = () => {
        count--;
    }
</script>

<h1>
    {count}
</h1>

<button on:click={increment}>
    Increment
</button>

<button on:click={decrement}>
    Decrement
</button>
