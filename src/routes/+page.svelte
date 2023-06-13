<script>
    let count = 0;

    const increment = () => {
        count++;
        console.log("incrementing");
    }

    const decrement = () => {
        count--;
        console.log("decrementing");
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
