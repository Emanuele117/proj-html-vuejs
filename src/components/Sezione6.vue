<template>
  <div class="container d-flex justify-content-center">
    <div class="cards1">
      <img src="../assets/blog92x.jpg" alt="cappuccino" class="img-card1" />
      <h2 class="t-card1">THE BEST COFFE IN TOWN</h2>
      <p class="p-card1">By admin | January 7th, 2020 | Categories: News</p>
    </div>
    <div class="cards2">
      <img src="../assets/blog72x.jpg" alt="" class="img-card2" />
      <h2 class="t-card2">DISCOVER OUR NEW MENU</h2>
      <p class="p-card2">By admin | January 7th, 2020 | Categories: News</p>
    </div>
    <div class="cards3">
      <img src="../assets/blog82x.jpg" alt="" class="img-card3" />
      <h2 class="t-card3">WE KNOW ACCEPT SQUARE!</h2>
      <p class="p-card3">By admin | January 7th, 2020 | Categories: News</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.cards1 {
  height: 400px;
  width: 300px;
  margin: 1rem;

  .img-card1 {
    height: 100%;
    width: 100%;
    object-fit: cover;
  }
  .img-card1:hover {
    height: 450px;
    width: 300px;
  }

  .t-card1 {
    font-size: 20px;
    font-weight: bold;
    text-align: center;
    margin-top: 1rem;
  }
  .p-card1 {
    font-size: 10px;
    text-align: center;
  }
}
.cards2 {
  height: 400px;
  width: 300px;
  margin: 1rem;
  .img-card2 {
    height: 100%;
    width: 100%;
    object-fit: cover;
  }
  .img-card2:hover {
    height: 450px;
    width: 300px;
  }
  .t-card2 {
    font-size: 20px;
    font-weight: bold;
    text-align: center;
    margin-top: 1rem;
  }
  .p-card2 {
    font-size: 10px;
    text-align: center;
  }
}
.cards3 {
  height: 400px;
  width: 300px;
  margin: 1rem;
  .img-card3 {
    height: 100%;
    width: 100%;
    object-fit: cover;
  }
  .img-card3:hover {
    height: 450px;
    width: 300px;
  }
  .t-card3 {
    font-size: 20px;
    font-weight: bold;
    text-align: center;
    margin-top: 1rem;
  }
  .p-card3 {
    font-size: 10px;
    text-align: center;
  }
}
</style>