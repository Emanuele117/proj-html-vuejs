<template>
  <div class="container giornali">
    <div class="box-info">
      <img src="../assets/info52x.jpg" alt="" class="img-info" />
      <div class="contenitore-critiche">
        <p class="p-critiche">MERY MAXEY</p>
        <h2 class="titolo-critiche">THE GUARDIAN</h2>

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

        <span class="bottone-critiche">READ FULL ARTICLE</span>
      </div>
    </div>

    <div class="box-info">
      <img src="../assets/info12x.jpg" alt="" class="img-info" />
      <div class="contenitore-critiche">
        <p class="p-critiche">PATRICK MONROE</p>
        <h2 class="titolo-critiche">GLOBE AND MAIL</h2>

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

        <span class="bottone-critiche">READ FULL ARTICLE</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.giornali {
  display: flex;
  justify-content: center;
  margin-top: 2rem;
  .box-info {
    position: relative;
  }
  .contenitore-critiche {
    position: absolute;
    top: 1rem;
    padding: 100px;
    color: white;
    .fa-star {
      margin-top: 2rem;
      margin-bottom: 2rem;
      font-size: 12px;
      margin-right: 8px;
    }
    .p-testo {
      margin-bottom: 2rem;
    }
    .bottone-critiche {
      padding: 12px;
      color: white;
      font-size: 10px;
      border: 1px solid white;
    }
    .bottone-critiche:hover {
      color: black;
      background-color: white;
      font-weight: bold;
    }
  }

  .img-info {
    height: 600px;
    margin: 1.5rem;
    filter: brightness(0.4);
  }
}
</style>