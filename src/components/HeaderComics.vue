<template>
  <header>
    <div class="container">
      <div>
        <img src="../assets/img/dc-logo.png" alt="" />
      </div>

      <div>
        <ul>
          <li><a href="">Characters</a></li>
          <li><a href="">Comics</a></li>
          <li><a href="">Movies</a></li>
          <li><a href="">Tv</a></li>
          <li><a href="">Games</a></li>
          <li><a href="">Collectibles</a></li>
          <li><a href="">Videos</a></li>
          <li><a href="">Fans</a></li>
          <li><a href="">News</a></li>
          <li><a href="">Shop</a></li>
        </ul>
      </div>
    </div>
    <HeaderComicsBlack />

  </header>
</template>

<script>
import HeaderComicsBlack from "./HeaderComicsBlack.vue";

export default {
  name: "HeaderComics",

  components: {
    HeaderComicsBlack,
  },
};
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.container {
  background-color: white;
  width: 80%;
  margin: auto;
  padding: 10px 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

ul {
  display: flex;

  li {
    list-style: none;
    margin: 0 10px;

    a {
      color: black;
      text-decoration: none;
    }

    a:hover {
      border-bottom: 2px solid blue;
    }
  }
}

header img {
  width: 60%;
}
</style>
