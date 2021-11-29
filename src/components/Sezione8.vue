<template>
  <div class="container d-flex justify-content-center generale">
    <div class="foglio-menu">
      <h1 class="titolo-menu">HORS D'OEUVRES</h1>
      <div class="testo-menu">
        <div class="titolo-prezzo d-flex justify-content-between">
          <h2 class="nome-sushi">AHI SALMON NIGIRI</h2>
          <p class="prezzo">$48</p>
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="testo-menu">
        <div class="titolo-prezzo d-flex justify-content-between">
          <h2 class="nome-sushi">UMI MASU SALAD</h2>
          <p class="prezzo">$21</p>
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="testo-menu">
        <div class="titolo-prezzo d-flex justify-content-between">
          <h2 class="nome-sushi">TEMAKI WITH CRAB</h2>
          <p class="prezzo">$32</p>
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="testo-menu">
        <div class="titolo-prezzo d-flex justify-content-between">
          <h2 class="nome-sushi">CALIFORNIA ROLLS</h2>
          <p class="prezzo">$22</p>
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
    </div>

    <!-- primo foglio menu -->

    <div class="foglio-menu2">
      <img src="../assets/misc22x.jpg" alt="" class="img-sfondo" />
      <div class="testo-totale">
        <h1 class="titolo-menu2">HORS D'OEUVRES</h1>
        <div class="testo-menu2">
          <div class="titolo-prezzo2 d-flex justify-content-between">
            <h2 class="nome-sushi2">AHI SALMON NIGIRI</h2>
            <p class="prezzo2">$48</p>
          </div>
          <p class="p-menu2">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
          </p>
        </div>
        <div class="testo-menu2">
          <div class="titolo-prezzo2 d-flex justify-content-between">
            <h2 class="nome-sushi2">UMI MASU SALAD</h2>
            <p class="prezzo2">$21</p>
          </div>
          <p class="p-menu2">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
          </p>
        </div>
        <div class="testo-menu2">
          <div class="titolo-prezzo2 d-flex justify-content-between">
            <h2 class="nome-sushi2">TEMAKI WITH CRAB</h2>
            <p class="prezzo2">$32</p>
          </div>
          <p class="p-menu2">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
          </p>
        </div>
        <div class="testo-menu2">
          <div class="titolo-prezzo2 d-flex justify-content-between">
            <h2 class="nome-sushi2">CALIFORNIA ROLLS</h2>
            <p class="prezzo2">$22</p>
          </div>
          <p class="p-menu2">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
          </p>
        </div>
      </div>
    </div>

    <!-- secondo foglio menu -->

    <div class="foglio-menu">
      <h1 class="titolo-menu">HORS D'OEUVRES</h1>
      <div class="testo-menu">
        <div class="titolo-prezzo d-flex justify-content-between">
          <h2 class="nome-sushi">AHI SALMON NIGIRI</h2>
          <p class="prezzo">$48</p>
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="testo-menu">
        <div class="titolo-prezzo d-flex justify-content-between">
          <h2 class="nome-sushi">UMI MASU SALAD</h2>
          <p class="prezzo">$21</p>
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="testo-menu">
        <div class="titolo-prezzo d-flex justify-content-between">
          <h2 class="nome-sushi">TEMAKI WITH CRAB</h2>
          <p class="prezzo">$32</p>
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="testo-menu">
        <div class="titolo-prezzo d-flex justify-content-between">
          <h2 class="nome-sushi">CALIFORNIA ROLLS</h2>
          <p class="prezzo">$22</p>
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.generale {
  height: 650px;
  margin-top: 6rem;

  .foglio-menu {
    background-color: lightgray;
    height: 600px;
    width: 400px;
    padding: 55px;
    margin-top: 2rem;

    .testo-menu {
      margin-bottom: 2rem;
    }
    .titolo-menu {
      font-size: 25px;
      font-weight: bold;
      margin-bottom: 3rem;
    }
    .nome-sushi {
      font-size: 18px;
      font-weight: bold;
    }
    .prezzo {
      font-size: 12px;
      margin-top: 2px;
    }
  }
  .foglio-menu2 {
    background-color: black;
    height: 600px;
    width: 400px;
    margin-bottom: 1rem;

    position: relative;
    .testo-totale {
      position: absolute;
      top: 0;
      padding: 55px;

      height: 600px;
    }

    .img-sfondo {
      height: 100%;
      width: 100%;
      object-fit: cover;
      filter: brightness(0.3);
    }
    .testo-menu2 {
      margin-bottom: 2rem;

      .p-menu2 {
        color: lightgray;
        opacity: 70%;
      }
    }
    .titolo-menu2 {
      font-size: 25px;
      font-weight: bold;
      margin-bottom: 3rem;
      color: white;
    }
    .nome-sushi2 {
      font-size: 18px;
      font-weight: bold;
      color: white;
    }
    .prezzo2 {
      font-size: 12px;
      margin-top: 2px;
      color: lightgray;
    }
  }
}
</style>