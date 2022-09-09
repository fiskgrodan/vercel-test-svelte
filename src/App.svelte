<script>
  import Summer from "./components/Summer.svelte";
</script>

<main>
  <h1>Svelte static</h1>
  <Summer />
</main>

<style>
  :global(:root) {
    font-family: "OpenDyslexic", sans-serif;
    font-size: 16px;
    line-height: 24px;
    font-weight: 400;

    color-scheme: normal;
    color: orange;
    background-color: black;

    font-synthesis: none;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    -webkit-text-size-adjust: 100%;
  }

  :global(html, body) {
    margin: 0;
    padding: 0;
  }

  :global(::selection) {
    background-color: orange;
    color: black;
  }

  main {
    padding: 20px 40px;
  }

  h1 {
    margin-block-start: 20px;
    margin-block-end: 20px;
  }
</style>
