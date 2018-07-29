<template>
  <nav class="navbar is-fixed-top is-dark is-mobile" role="navigation" aria-label="main-navigation">
    <div class="navbar-menu">
      <div class="navbar-end">
        <nuxt-link class="navbar-item" to="/">Home</nuxt-link>
        <nuxt-link class="navbar-item" to="/projects">Projects</nuxt-link>
      </div>
    </div>
  </nav>
</template>

<script>
  export default {
    name: 'NavigationBar'
  }
</script>

<style>
  .navbar, .navbar-menu, .navbar-start, .navbar-end {
    display: flex;
    align-items: stretch;
  }

  .navbar-menu {
    flex-grow: 1;
    flex-shrink: 0;
  }

  .navbar-end {
    justify-content: flex-end;
  }
</style>
