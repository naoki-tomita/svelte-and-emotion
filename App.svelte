<script lang="ts">
  import { css } from "@emotion/css";

  let x = 0;
  function increment() {
    x++;
  }
</script>

<main>
  <div>{x}</div>
  <button
    class={css`
      color: red;
    `}
    on:click={increment}
  >+</button>
</main>

<style>
</style>
