<template>
  <nav class="navbar is-fixed-top is-dark" role="navigation" aria-label="main-navigation">
    <div class="navbar-menu is-active">
      <div class="navbar-end">
        <router-link class="navbar-item" to="/">Home</router-link>
        <router-link class="navbar-item" to="/projects">Projects</router-link>
        <router-link class="navbar-item" to="/hire">Hire me</router-link>
      </div>
    </div>
  </nav>
</template>

<script>
  export default {
    name: 'NavigationBar'
  }
</script>
