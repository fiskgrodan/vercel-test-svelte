<script>
  let left = 0;
  let right = 0;

  $: sum = left + right;
</script>

<section>
  <div><input bind:value={left} type="number" /></div>
  <div><input bind:value={right} type="number" /></div>
  <div>{sum}</div>
</section>

<style>
  input {
    background-color: black;
    color: darkorange;
    border: 1px solid black;
    box-shadow: none;
    outline: none;
    font-family: "OpenDyslexic", sans-serif;
    font-size: 16px;
    padding: 0;
    margin: 0 0 10px 0;
  }

  input[type="number"]::-webkit-inner-spin-button,
  input[type="number"]::-webkit-outer-spin-button {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
  }
</style>
