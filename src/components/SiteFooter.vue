<template>
  <div class="hero-img">
    <img src="../assets/footer2x.jpg" alt="" class="img-footer" />
    <div class="testo">
      <img src="../assets/logo-restaurant.png" alt="" class="immagine-logo" />
      <p class="p-logo">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consequuntur
        nulla dolor.
      </p>
      <div class="icone d-flex justify-content-center">
        <i class="fab fa-facebook icona"></i>
        <i class="fab fa-twitter icona"></i>
        <i class="fab fa-youtube icona"></i>
        <i class="fab fa-instagram icona"></i>
        <i class="fab fa-invision icona"></i>
      </div>
    </div>
    <div class="copyright">
      <div class="copy">
        <p>
          Copyright 2012-2019 Avada | All Right Reserved | Powered by WordPress
          | ThemeFusion
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.hero-img {
  width: 1518px;
  height: 500px;
  position: relative;

  .testo {
    position: absolute;
    top: 12rem;
    margin-left: 35rem;
    text-align: center;
    width: 400px;
    .immagine-logo {
      height: 40px;
    }
    .p-logo {
      margin-top: 2rem;
      margin-bottom: 2rem;
      color: white;
      opacity: 70%;
    }
    .icone {
      .fa-facebook,
      .fa-twitter,
      .fa-youtube,
      .fa-instagram,
      .fa-invision {
        font-size: 32px;
        color: white;
        margin: 6px;
      }
    }
  }
  .img-footer {
    height: 100%;
    width: 100%;
    object-fit: cover;
  }
  .copyright {
    background-color: black;
    height: 80px;
    position: relative;
    .copy {
      position: absolute;
      top: 0;
      margin-top: 35px;
      margin-left: 38rem;
      color: white;
      opacity: 70%;
      font-size: 8px;
    }
  }
}
</style>