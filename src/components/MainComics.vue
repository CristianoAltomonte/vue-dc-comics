<template>
  <main>
    <div class="container-main">
      <div class="nav-main">
      <ul>
        <li><img src="../assets/img/buy-comics-digital-comics.png" alt="" /></li>
        <li><img src="../assets/img/buy-comics-merchandise.png" alt="" /></li>
        <li><img src="../assets/img/buy-comics-shop-locator.png" alt="" /></li>
        <li><img src="../assets/img/buy-comics-subscriptions.png" alt="" /></li>
        <li><img src="../assets/img/buy-dc-power-visa.svg" alt="" /></li>
      </ul>
    </div>
    </div>
    
  </main>
</template>

<script>
export default {
  name: "MainComics",
};
</script>

<style style scoped lang="scss">

.nav-main {
  width: 80%;
  margin: auto;
}

.container-main {
  padding: 10px;
  background-color: rgba(2, 130, 249, 1);
}

.nav-main img {
  width: 40px;
}

ul {
  display: flex;
  justify-content: space-around;
  align-items: center;

  li {
    list-style: none;
    margin: 0 10px;
  }
}

</style>