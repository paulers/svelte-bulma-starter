<script>
  import Nav from '$components/Nav.svelte';
  
</script>

<main>
  <Nav/>
  <slot></slot>
</main>

<style global lang="scss">
@import 'bulma/bulma.sass';
</style>