<template>
  <div class="container general">
    <div class="contenitore-img">
      <img src="../assets/blog72x.jpg" alt="" class="img-orange" />
    </div>
    <div class="contenitore-black">
      <div class="contenitore-critiche">
        <p class="p-critiche">MEGGY STEWART</p>
        <h2 class="titolo-critiche">NEW YORK TIMES</h2>

        <div class="icons">
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
        </div>

        <p class="p-testo">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum dolorem
          aut sapiente veniam ea enim reiciendis.
        </p>
        <p class="p-testo">
          Lorem ipsum dolor sit amet consectetur adipisicing elit Harum dolorem
          aut sapiente .
        </p>
        <span class="bottone-critiche">READ FULL ARTICLE</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.general {
  display: flex;
  justify-content: center;
  .img-orange {
    height: 600px;
  }
  .contenitore-black {
    background-color: black;
    height: 600px;
    width: 550px;
    .contenitore-critiche {
      width: 400px;
      padding: 50px;
      margin-left: 4rem;
      margin-top: 3rem;

      .p-critiche {
        color: white;
        opacity: 70%;
        font-size: 12px;
      }
      .titolo-critiche {
        font-weight: bold;
        color: white;
        font-size: 30px;
      }
      .fa-star {
        color: white;
        font-size: 12px;
        margin-top: 2rem;
      }
      .p-testo {
        color: white;
        opacity: 70%;
        font-size: 12px;
        margin-top: 2rem;
        margin-bottom: 3rem;
      }
      .bottone-critiche {
        padding: 12px;
        color: white;
        font-size: 10px;
        border: 1px solid white;
      }
    }
  }
}
</style>