<script>
  import { page } from '$app/stores'
  console.log($page.params.singer);
</script>


  <main>
    <h1>{$page.params.singer}</h1>
  </main>

<style>
  main {
    font-variant: small-caps;
  }
</style>