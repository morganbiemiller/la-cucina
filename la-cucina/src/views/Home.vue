<template>
  <div class="home">
    <div class="home-img">
      <img alt="La Cucina Logo" src="../assets/imgs/la-cucina-full.svg">
    </div>
  </div>
</template>

<script>

export default {
  name: 'home',
  components: {
  }
}
</script>

<style lang="scss" scoped>

.home {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: -80px 0;
  height: calc(100vh - 40px);
}

.home-img {
  width: 60%;
  margin: 0 auto;
  min-width: 320px;
  max-width: 600px;
};
</style>

