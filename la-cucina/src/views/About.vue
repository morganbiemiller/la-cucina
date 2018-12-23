<template>
  <div class="about">
    <div class="about__info">
      <h1>This is an about page</h1>
      <p>
        Maria Biemiller, chef and owner of La Cucina has been providing delicious food for groups small and large for about 25 years. After much time spent providing meals for her family, hosting parties, competing in barbeque competitions and more she decided to turn her much loved hobby into a business in 2010. She wants to share her passion for cooking with the community by bringing food from her kitchen to yours.
      </p>
      <p>
        At La Cucina, we understand that people from the Rochester, New York area appreciate fine cuisine, and that is something that should never be compromised. Please take a look at our menus to see some of our most popular and specialty foods. If you have a specific dish in mind for your event that is not listed on our site, please don’t hesitate to ask us if it is possible to do. Maria and her small team want to work directly with you in creating the perfect menu for any occasion.
      </p>
    </div>
    <div class="about__image">
      <img src="./../assets/imgs/about/maria.jpg">
    </div>
  </div>
</template>

<style lang="scss" scoped>
.about {
  display: grid;
  grid-template-columns: 7fr 3fr;
  grid-gap: 60px;
}

.about__image {
  img {
    filter: grayscale(100%);
  }
}
</style>
