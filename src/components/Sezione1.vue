<template>
  <div class="container">
    <div class="contenitore-flex">
      <div class="testo">
        <p>
          Lorem ipsum dolor sit amet conseectetur adipisicing elit. Accusantium
          suscipit neque eaque fuga.
        </p>
        <h1>FOOD IS OUR COMMON GROUND, A UNIVERSAL EXPERIENCE.</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium
          suscipit neque eaque fuga.
        </p>
        <img src="../assets/signature.jpg" alt="" class="signature" />
      </div>
      <div class="img-california-rolls">
        <img src="../assets/california-rolls.jpg" alt="" class="img-rolls" />
        <p class="p-rolls">CALIFORNIA ROLLS - $22</p>
      </div>
    </div>
    <div class="contenitore-sushi">
      <div class="sushi1">
        <img src="../assets/sushi-1.png" alt="sushi1" class="img-sushi" />
        <h2 class="titolo-sushi">THE BEST TABLE IN TOWN</h2>
        <p class="p-sushi">
          Lorem ipsum dolor sit amet consectetur adipisicing elitsit amet
          consectetur.
        </p>
        <span class="bottone-sushi">EXPLORE THE MENU</span>
      </div>
      <!-- /explore the menu -->
      <div class="sushi1">
        <img src="../assets/sushi-2.png" alt="sushi1" class="img-sushi" />
        <h2 class="titolo-sushi">PERFECT FOR GROUPS</h2>
        <p class="p-sushi">
          Lorem ipsum dolor sit amet consectetur adipisicing elitsit amet
          consectetur.
        </p>
        <span class="bottone-sushi">MAKE A RESERVATION</span>
      </div>
      <!-- /make a reservation -->
      <div class="sushi1">
        <img src="../assets/sushi-3.png" alt="sushi1" class="img-sushi" />
        <h2 class="titolo-sushi">FRESH PRODUCE EVERYDAY</h2>
        <p class="p-sushi">
          Lorem ipsum dolor sit amet consectetur adipisicing elitsit amet
          consectetur.
        </p>
        <span class="bottone-sushi">LEARN MORE ABOUT US</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.container {
  margin-top: 15rem;
  .contenitore-flex {
    display: flex;
    justify-content: center;
  }
  .contenitore-sushi {
    display: flex;
    justify-content: center;
    margin-right: 8rem;
    margin-top: 6rem;
    .img-sushi {
      height: 60px;
    }
    .sushi1 {
      width: 250px;
      text-align: center;
      margin-left: 5rem;
    }
    .titolo-sushi {
      font-size: 18px;
      font-weight: bold;
      margin-top: 2rem;
      margin-bottom: 2rem;
    }
    .bottone-sushi {
      border: 1px solid lightgray;
      padding: 10px;
      font-size: 10px;
      font-weight: 600;
    }
    .bottone-sushi:hover {
      border: 2px solid black;
      font-weight: bold;
    }
  }

  .testo {
    width: 450px;
    margin-top: 50px;

    margin-right: 4rem;

    p {
      font-size: 15px;
    }
    h1 {
      font-weight: bold;
      font-size: 35px;
      margin-top: 3rem;
      margin-bottom: 3rem;
    }
    img {
      height: 100px;
    }
  }
  .img-california-rolls {
    width: 450px;
    position: relative;
    .img-rolls {
      height: 500px;
      width: 400px;
      filter: brightness(0.7);
    }
    .img-rolls:hover {
      filter: none;
    }
    .p-rolls {
      position: absolute;
      bottom: 0;
      margin-left: 140px;
      color: white;
      font-size: 12px;
    }
  }
}
</style>