<template>
  <div class="page--about page">
    <div class="page-heading">
      <h1>Menues</h1>
      <h2>About anything</h2>

      <Buffets></Buffets>
      <Desserts></Desserts>
    </div>
  </div>
</template>

<script>
import Buffets from './templates/Buffets.vue';
import Desserts from './templates/Desserts.vue';

export default {
  name: 'Menues',
  data() {
    return {
      msg: 'Hey There',
    };
  },

  components: {
    Buffets,
    Desserts
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  // @import './../assets/scss/main.scss';

</style>
