<script lang="ts">
  import placeholderLogo from './assets/placeholder.png'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div>
    <a href="https://github.com/rokija" target="_blank" rel="noreferrer">
      <img src={placeholderLogo} class="logo" alt="Vite Logo" />
    </a>
  </div>
  <h1>About Me</h1>
</main>

<style>
  .logo {
    height: 20em;
    padding: 5em;
    will-change: filter;
    transition: filter 500ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #ff6464aa);
  }
</style>
