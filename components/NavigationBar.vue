<template>
  <nav class="navbar is-fixed-top is-dark" role="navigation" aria-label="main-navigation">
    <div class="navbar-menu is-active">
      <div class="navbar-end">
        <nuxt-link class="navbar-item" to="/">Home</nuxt-link>
        <nuxt-link class="navbar-item" to="/projects">Projects</nuxt-link>
        <nuxt-link class="navbar-item" to="/hire">Hire me</nuxt-link>
      </div>
    </div>
  </nav>
</template>

<script>
  export default {
    name: 'NavigationBar'
  }
</script>
