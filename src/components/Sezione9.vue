<template>
  <div class="contenitore">
    <div class="contenitore-immagine">
      <img src="../assets/hero42x.jpg" alt="" class="img-piatto-sushi" />
      <div class="black">
        <div class="contenitore-title d-flex justify-content-between">
          <h1>BRAISED ABALONE</h1>
          <p class="p-prezzo">$52</p>
        </div>
        <div class="contenitore-linea">
          <span class="linea"></span>
        </div>
        <p class="p">
          Lorem ipsum dolor sit amet consectetur adipisicing elit amet
          consectetur !
        </p>
        <span class="bottone">VIEW IN THE MENU</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.contenitore-immagine {
  width: 1518px;
  height: 600px;
  position: relative;
  margin-top: 5rem;
  .img-piatto-sushi {
    height: 100%;
    width: 100%;
    object-fit: cover;
  }
}
.black {
  height: 450px;
  width: 350px;
  background-color: black;
  position: absolute;
  top: 0;
  margin: 5rem;
  margin-left: 10rem;
  padding: 3rem;
  .contenitore-title {
    color: white;
    .p-prezzo {
      font-size: 12px;
      margin-top: 10px;
    }
  }
  .contenitore-linea {
    height: 50px;
    margin-top: 2rem;
    display: flex;
    .linea {
      width: 50px;
      height: 1px;
      background-color: white;
      margin-top: 1rem;
    }
  }
  .p {
    color: white;
    margin-bottom: 2rem;
  }
  .bottone {
    padding: 10px;
    color: white;
    font-size: 10px;
    border: 1px solid white;
  }
}
</style>