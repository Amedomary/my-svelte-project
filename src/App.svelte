<script>
  import HeroBlock from './HeroBlock.svelte';
  import Footer from './Footer.svelte';
  export let name;
</script>

<main>
  <HeroBlock head={'PlayBook'} />
  <h1>Hello {name}!</h1>
  <Footer />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }
</style>
