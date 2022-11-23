<template>
  <footer>
    <div class="background-footer">
      <div class="nav-footer">
        <div class="lista-footer">
          <div>
            <ul>
              <li><h2>DC COMICS</h2></li>
              <li><a href="">Characters</a></li>
              <li><a href="">Comics</a></li>
              <li><a href="">Movies</a></li>
              <li><a href="">Tv</a></li>
              <li><a href="">Games</a></li>
              <li><a href="">Videos</a></li>
              <li><a href="">New</a></li>
            </ul>
            <ul>
              <li><h2>SHOP</h2></li>
              <li><a href="">Shop DC</a></li>
              <li><a href="">Shop DC Collectibles</a></li>
            </ul>
          </div>
          <div>
            <ul>
              <li><h2>DC</h2></li>
              <li><a href="">Ciao</a></li>
              <li><a href="">Sono</a></li>
              <li><a href="">IO</a></li>
            </ul>
            <ul>
              <h2>SITES</h2>
              <li><a href="">Ciao</a></li>
              <li><a href="">Sono</a></li>
              <li><a href="">IO</a></li>
            </ul>
          </div>
        </div>

        <div>
          <img src="../assets/img/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </div>
    <FooterComicsBottom />
  </footer>
</template>

<script>
import FooterComicsBottom from "./FooterComicsBottom.vue";

export default {
  name: "FooterComics",

  components: {
    FooterComicsBottom,
  },
};
</script>

<style style scoped lang="scss">
.background-footer {
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: contain;
}

ul {
  color: white;
  padding: 10px 0;

  li {
    
    list-style: none;
    margin: 20px;
    line-height: 5%;
    color: white;

  }

  a {
    text-decoration: none;
    color: grey;
  }
  
}

.nav-footer {
  width: 80%;
  margin: auto;
  display: flex;
  justify-content: space-between;
  padding: 30px 0;
  align-items: center;
}

.lista-footer {
  display: flex;
}
img {
  width: 60%;
}
</style>