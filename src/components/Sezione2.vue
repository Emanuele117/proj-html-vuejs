<template>
  <div class="contenitore-general">
    <img src="../assets/slider32x.jpg" alt="" class="img-sushi" />
    <div class="testo">
      <div class="contenitore-linea">
        <span class="linea"></span>
        <p class="p-linea">FINE DINING EXPERIENCE</p>
      </div>
      <div class="menu">
        <h1 class="titolo-menu">THE BEST TABLE IN TOWN</h1>
        <p class="p-menu">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Saepe minus
          sequi hic voluptatum
        </p>
        <span class="bottone">EXPLORE THE MENU</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.contenitore-general {
  display: flex;
  margin-top: 6rem;
  .img-sushi {
    width: 900px;
    height: 100vh;
  }
  .testo {
    background-color: black;
    height: 100vh;
    width: 700px;
    .contenitore-linea {
      display: flex;
      margin-left: 6rem;
      margin-top: 11rem;
      .p-linea {
        margin-left: 2rem;
        color: white;
        opacity: 70%;
        font-size: 12px;
      }
      .linea {
        width: 40px;
        height: 1px;
        background-color: grey;
        margin-top: 8px;
      }
    }
    .menu {
      margin-left: 170px;
      margin-top: 2rem;
      width: 330px;
      .titolo-menu {
        font-weight: bold;
        color: white;
        font-size: 40px;
        margin-bottom: 3rem;
      }
      .p-menu {
        color: white;
        opacity: 70%;
        margin-bottom: 3rem;
        font-size: 15px;
      }
      .bottone {
        padding: 10px;
        color: white;
        font-size: 10px;
        border: 1px solid white;
      }
    }
  }
}
</style>