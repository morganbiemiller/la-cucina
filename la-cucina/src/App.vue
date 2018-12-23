<template>
  <div id="app" class="app">
    <top-nav/>
    <router-view class="content"/>
  </div>
</template>

<script>
import TopNav from '@/components/TopNav.vue'

export default {
  name: 'App',

  components: {
    TopNav
  }
}
</script>

<style lang="scss">
@import "./assets/import.scss";

html,
body {
  height: 100%;
  width: 100%;
}

body {
  @include type-standard();
  background-color: $bg;
  margin: 0;
}

img {
  width: 100%;
}

h1,
h2,
h3,
h4 {
  margin-top: 0;
}

.content {
  @include padding();
}

a {
  text-decoration: none;
  // @include type-medium();

  &:hover {
    transform: translateY(2px);
    @include transition();
  }
}

p {
  line-height: 1.8;
}

.app {
  display: grid;
  grid-template-rows: 80px 1fr;
}
</style>

