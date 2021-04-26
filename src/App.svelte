<script>
  import HeroBlock from './HeroBlock.svelte';
  import Footer from './Footer.svelte';
  import NeedCouch from './NeedCouch.svelte';
  export let name;
</script>

<main>
  <HeroBlock head={'PlayBook'} />
  <NeedCouch />
  <NeedCouch />
  <!-- <h1>Hello {name}!</h1> -->
  <Footer />
</main>

<style>
  main {
    text-align: center;
    padding: 4em 2em;
    margin: 0 auto;
  }
</style>
