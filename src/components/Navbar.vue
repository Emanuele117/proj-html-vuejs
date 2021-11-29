<template>
  <div class="contenitore-navbar">
    <a href="home" class="home">{{ home }}</a>
    <a href="history">{{ history }}</a>
    <a href="team">{{ team }}</a>
    <a href="menu">{{ menu }}</a>
    <a href="takeout">{{ takeout }}</a>
    <a href="bulletin">{{ bulletin }}</a>
    <a href="reservations">{{ reservation }}</a>
    <i class="fas fa-shopping-cart"></i>
  </div>
</template>

<script>
export default {
  props: {
    home: String,
    history: String,
    team: String,
    menu: String,
    takeout: String,
    bulletin: String,
    reservation: String,
  },
};
</script>

<style lang="scss">
.contenitore-navbar {
  position: absolute;
  top: 0;
  margin-top: 3rem;
  margin-left: 6rem;
  a {
    text-decoration: none;
    color: white;
    opacity: 70%;
    margin-right: 2.5rem;
  }
  a:hover {
    color: white;
    opacity: 100%;
  }
  .home {
    color: white;
    opacity: 100%;
  }
  .fa-shopping-cart {
    color: white;
    font-size: 15px;
  }
  .fa-shopping-cart:hover {
    font-size: 18px;
    cursor: pointer;
  }
}
</style>