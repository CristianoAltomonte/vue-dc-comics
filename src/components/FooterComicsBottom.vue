<template>
  <footer>
    <div class="sing-up">
      <div class="bottone">
        <span class="sign">SIGN UP NOW !</span>
      </div>

      <div class="social-icons">

        <div>
          <span class="follow">FOLLOW US</span>
        </div>
        
        <div>
          <img src="../assets/img/footer-facebook.png" alt="#" />
          <img src="../assets/img/footer-twitter.png" alt="#" />
          <img src="../assets/img/footer-youtube.png" alt="#" />
          <img src="../assets/img/footer-pinterest.png" alt="#" />
          <img src="../assets/img/footer-periscope.png" alt="#" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComicsBottom",
};
</script>

<style>
footer {
  background-color: rgba(48, 48, 48, 1);
}

img {

  color: white;
  margin: 5px;
}

.sing-up {
  width: 80%;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 9px 0;
}

.bottone {
  border: 2px solid rgba(2, 130, 249, 1);
  padding: 5px;
}

.social-icons{

  display: flex;
  align-items: center;
  gap: 10px;

}

.follow{
  color: rgba(2, 130, 249, 1);
}

.sign{
  color: white;
}

</style>