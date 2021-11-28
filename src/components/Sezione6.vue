<template>
  <div class="container d-flex justify-content-center">
    <div class="cards">
      <img src="../assets/blog92x.jpg" alt="cappuccino" class="img-card" />
      <h2 class="t-card">THE BEST COFFE IN TOWN</h2>
      <p class="p-card">By admin | January 7th, 2020 | Categories: News</p>
    </div>
    <div class="cards">
      <img src="../assets/blog72x.jpg" alt="" class="img-card" />
      <h2 class="t-card">DISCOVER OUR NEW MENU</h2>
      <p class="p-card">By admin | January 7th, 2020 | Categories: News</p>
    </div>
    <div class="cards">
      <img src="../assets/blog82x.jpg" alt="" class="img-card" />
      <h2 class="t-card">WE KNOW ACCEPT SQUARE!</h2>
      <p class="p-card">By admin | January 7th, 2020 | Categories: News</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.img-card {
  height: 400px;
  width: 300px;
  object-fit: cover;
  margin: 1rem;
}
.t-card {
  font-size: 20px;
  font-weight: bold;
  text-align: center;
  margin-top: 1rem;
}
.p-card {
  font-size: 10px;
  text-align: center;
}
</style>