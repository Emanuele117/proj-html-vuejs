<template>
  <div class="contenitore-generale">
    <div class="logo">
      <img
        src="../assets/logo-restaurant.png"
        alt="logo-avada"
        class="logo-avada"
      />
      <div class="contenitore-linea">
        <span class="linea"></span>
        <p class="p-linea">THE BEST TABLE IN TOWN</p>
      </div>
      <div class="menu">
        <h1 class="titolo-menu">FINE DINING EXPERIENCE</h1>
        <p class="p-menu">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Saepe minus
          sequi hic voluptatum
        </p>
        <span class="bottone">EXPLORE THE MENU</span>
      </div>
    </div>
    <div class="hero-bar">
      <img src="../assets/slider52x.jpg" alt="" class="img-bar" />
      <Navbar
        v-for="item in items"
        :key="item.id"
        :home="item.home"
        :history="item.history"
        :team="item.team"
        :menu="item.menu"
        :takeout="item.takeout"
        :bulletin="item.bulletin"
        :reservation="item.reservations"
      />
    </div>
  </div>
</template>

<script>
import Navbar from "./Navbar.vue";
export default {
  data() {
    return {
      items: [
        {
          home: "Home",
          history: "Culinary History",
          team: "Our Team",
          menu: "Our Menu",
          takeout: "Takeout",
          bulletin: "Bulletin",
          reservations: "Reservations",
        },
      ],
    };
  },
  components: {
    Navbar,
  },
};
</script>

<style lang="scss">
.contenitore-generale {
  display: flex;
  height: 600px;
  width: 100%;
  .logo {
    background-color: black;
    width: 600px;
    height: 100vh;
    .logo-avada {
      width: 250px;
      margin-left: 4rem;
      margin-top: 2rem;
    }
    .contenitore-linea {
      display: flex;
      margin-left: 4rem;
      margin-top: 7rem;
      .p-linea {
        margin-left: 2rem;
        color: white;
        opacity: 70%;
        font-size: 12px;
      }
      .linea {
        width: 30px;
        height: 1px;
        background-color: grey;
        margin-top: 8px;
      }
    }
    .menu {
      width: 280px;
      margin-left: 122px;
      margin-top: 2rem;
      .titolo-menu {
        font-weight: bold;
        color: white;
        font-size: 45px;
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
      .bottone:hover {
        color: black;
        background-color: white;
        font-weight: bold;
      }
    }
  }
  .img-bar {
    width: 1000px;
    height: 100vh;
    position: relative;
  }
}
</style>