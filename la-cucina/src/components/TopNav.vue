<template>
  <div class="top-nav">
    <router-link to="/" class="top-nav__logo">
      <img alt="La Cucina logo" src="./../assets/imgs/la-cucina-icon.svg">
    </router-link>
    <div class="top-nav--right">
      <router-link class="top-nav__link" to="/menus">Menus</router-link>
      <router-link class="top-nav__link" to="/about">About</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TopNav',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import "./../assets/import.scss";

.top-nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  @include padding();
}

.top-nav__logo {
  display: flex;
  align-items: flex-start;
  width: 100px;
}

.top-nav__link {
  padding: 0 $padding;
  color: $off-black;
  display: inline-block;
}
</style>
