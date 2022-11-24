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

            <ul class="shop">
              <li><h2>SHOP</h2></li>
              <li><a href="">Shop DC</a></li>
              <li><a href="">Shop DC Collectibles</a></li>
            </ul>
          </div>

          <div>
            <ul>
              <li><h2>DC</h2></li>
              <li><a href="">Terms Of Use</a></li>
              <li><a href="">Privacy policy (New)</a></li>
              <li><a href="">Ad Choices</a></li>
              <li><a href="">Advertising</a></li>
              <li><a href="">Jobs</a></li>
              <li><a href="">Subscriptions</a></li>
              <li><a href="">Talent Workshops</a></li>
              <li><a href="">CPSC Certificates</a></li>
              <li><a href="">Ratings</a></li>
              <li><a href="">Shop Help</a></li>
              <li><a href="">Contact Us</a></li>
            </ul>
          </div>

          <div>
            <ul>
              <li><h2>SITES</h2></li>
              <li><a href="">DC Magazine</a></li>
              <li><a href="">MAD Kids</a></li>
              <li><a href="">DC Kids</a></li>
              <li><a href="">DC Universe</a></li>
              <li><a href="">DC Power Visa</a></li>
            </ul>
          </div>

        </div>

        <div class="img-bg"></div>
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
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;

}

ul {
  color: white;
 
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
 
}

.lista-footer {
  display: flex;
  padding: 50px 0;
}

img {
  width: 60%;
}

.img-bg {
  background-image: url("../assets/img/dc-logo-bg.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  width: 55%;
  height: 600px;
}

.shop{
  padding-top: 1px;
}

</style>