<script lang="ts">
import { defineComponent } from 'vue'
import Example from './views/example/index.vue'

export default defineComponent({
  name: 'App',
  components: {
    Example,
  },
})
</script>

<template>
  <a
    class="github-fork-ribbon"
    href="https://github.com/mirari/v-viewer"
    title="Fork me on GitHub"
  >Fork me on GitHub</a>
  <section
    class="hero is-primary"
    style="margin-bottom: 2em"
  >
    <div class="hero-body">
      <div class="container">
        <div class="columns is-vcentered">
          <div class="column">
            <p class="title is-1">
              v-viewer
            </p>
            <p class="subtitle is-4">
              Image viewer component for vue, supports rotation, scale, zoom and so on, based on <a
                href="https://github.com/fengyuanchen/viewerjs"
                target="_blank"
              >viewer.js</a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <div
    class="container"
    style="margin-bottom: 30px"
  >
    <Example />
  </div>
  <footer class="footer">
    <div class="container">
      <div class="content has-text-centered">
        <p>
          <a
            href="http://mirari.cc"
            target="_blank"
            title="mirari.cc"
          >
            <strong>mirari.cc</strong>
          </a>
          ·  GitHub
          <a
            href="https://github.com/mirari"
            target="_blank"
            title="GitHub"
          >
            @mirari
          </a>
        </p>
      </div>
    </div>
  </footer>
</template>
