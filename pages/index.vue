<template>
  <div>
    <section class="startpage-hero">
      <div>
        <h1 class="main-title is-size-1-mobile">
          John-Robin Tell
        </h1>
        <h2 class="subtitle is-size-3-mobile">
          Fullstack Developer
        </h2>
        <div>
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

    <section class="section section-spacing has-background-dark-blue">
      <div class="container">
        <h2 class="title has-text-centered subtitle has-text-white"><i>Simplicity</i></h2>
        <h3 class="title has-text-centered has-text-white">Is my motto and what I strive for</h3>
      </div>
    </section>

    <section class="section section-spacing has-background-light">
      <div class="container">
        <h2 class="title has-text-centered subtitle">Technologies I specify in</h2>
        <nav class="level">
          <div class="level-item has-text-centered">
            <div>
              <p class="title">VueJS</p>
              <p>A frontend framework written in <strong>JavaScript</strong></p>
            </div>
          </div>
          <div class="level-item has-text-centered">
            <div>
              <p class="title">Laravel</p>
              <p>A backend <strong>PHP</strong> framework</p>
            </div>
          </div>
          <div class="level-item has-text-centered">
            <div>
              <p class="title">PWA</p>
              <p>Progressive Web Apps</p>
            </div>
          </div>
        </nav>
      </div>
    </section>

    <section class="section has-background-grey-dark">
      <div class="container">
        <h2 class="title has-text-centered subtitle has-text-white">Latest Projects</h2>
      </div>
    </section>

    <section class="section has-background-grey-darker is-paddingless">
      <div class="project">
        <img class="project-image" src="https://res.cloudinary.com/jrtell/image/upload/c_scale,f_auto,q_auto,w_850,fl_progressive/v1532700679/jrtell/game_screenshot.png">
        <div class="project-text">
          <h2 class="title has-text-white">Nordland</h2>
          <div class="content has-text-white">
            A browser RPG kind of game, with an emphasis on Player versus Player combat in real-time with the help of Websockets.
          </div>
          <div class="tags">
            <span class="tag is-success">VueJS</span>
            <span class="tag is-danger">Lumen</span>
            <span class="tag is-info">Webpack</span>
            <span class="tag is-info">Socket.io</span>
            <span class="tag is-success">Node.js</span>
            <span class="tag is-primary">Bulma</span>
            <span class="tag is-danger">Sass</span>
          </div>
        </div>
      </div>
    </section>

    <section class="section has-background-grey-dark is-paddingless">
      <div class="project project-reverse">
        <img class="project-image" src="https://res.cloudinary.com/jrtell/image/upload/c_scale,f_auto,q_auto,w_850,fl_progressive/v1532702339/jrtell/vanilla.jpg">
        <div class="project-text">
          <h2 class="title has-text-white">Airsoft</h2>
          <div class="content has-text-white">
            Eventing site - A project to gather all of Sweden's airsoft events in one place. Built as a PWA (Progressive Web App).
          </div>
          <div class="tags">
            <span class="tag is-success">VueJS</span>
            <span class="tag is-danger">Laravel</span>
            <span class="tag is-info">Webpack</span>
            <span class="tag is-danger">Sass</span>
            <span class="tag is-primary">Bootstrap 4</span>
          </div>
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

<style lang="scss">
  .startpage-hero {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: url('https://res.cloudinary.com/jrtell/image/upload/c_crop,fl_progressive,q_auto,w_1920,h_900/v1532632023/jrtell/bg.jpg') center top no-repeat;
    background-size: cover;
    background-attachment: fixed;
  }

  .main-title {
    font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
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

  .has-background-dark-blue {
    background-color: #35495e;
  }

  .section-spacing {
    padding: 100px 0;
  }

  .project {
    display: flex;
    align-items: center;

    @media screen and (max-width: 992px) {
      display: block;
    }
  }

  .project-reverse {
    flex-direction: row-reverse;
  }

  .project-text {
    width: 60%;
    order: 2;
    padding: 2em 4em;

    @media screen and (max-width: 992px) {
      width: 100%;
    }
  }

  .project-image {
    width: 40%;
    order: 1;

    @media screen and (max-width: 992px) {
      width: 100%;
    }
  }
</style>

