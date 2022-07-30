<script>
  let upcount = 0
  const increment = () => {
    upcount += 2
  }
</script>

<button on:click={increment}>
  👍: {upcount}
</button>

<style>
  button {
    font-family: inherit;
    font-size: 1.2em;
    padding: 1em 2em;
    color: aliceblue;
    background-color: rgba(236, 224, 220, 0.1);
    border-radius: 2em;
    border: 2px solid rgba(229, 224, 223, 0);
    outline: none;
    width: 200px;
    font-variant-numeric: tabular-nums;
    cursor: pointer;
  }

  button:focus {
    border: 2px solid #ff3e00;
  }

  button:active {
    background-color: rgba(239, 232, 230, 0.2);
  }
</style>
