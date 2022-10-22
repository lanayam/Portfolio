<script>
// @ts-nocheck

  import About from "./components/About.svelte";
  import NavBar from "./components/NavBar.svelte";
</script>

<main>
  <NavBar />
  <div>
    <About />
  </div>
</main>

<style>
  main {
    margin: 1rem;
    font-size: 1.25rem;
  }
</style>