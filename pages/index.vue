<template>
  <div>
    <section class="startpage-hero">
      <div>
        <h1 class="title is-size-1-mobile">
          John-Robin Tell
        </h1>
        <h2 class="subtitle is-size-3-mobile">
          Fullstack Developer
        </h2>
        <div class="links">
          <a
            href="https://www.linkedin.com/in/john-robin-tell-b8bb235b/"
            target="_blank"
            class="button--grey">LinkedIn</a>
          <a
            href="https://github.com/john-robin"
            target="_blank"
            class="button--grey">GitHub</a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.startpage-hero {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: url('http://res.cloudinary.com/jrtell/image/upload/c_scale,fl_progressive,q_auto,w_1920/v1532632023/bg.jpg') center top;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #273143;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

