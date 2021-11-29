<template>
  <div>
    <Sezione1 />
    <Sezione2 />

    <p class="p-section">What critics are saying about us</p>

    <Sezione3 />
    <Sezione4 />
    <Sezione5 />

    <p class="p-section">Latest news e promotions</p>

    <Sezione6 />
    <Sezione7 />
    <Sezione8 />
  </div>
</template>

<script>
import Sezione1 from "./Sezione1.vue";
import Sezione2 from "./Sezione2.vue";
import Sezione3 from "./Sezione3.vue";
import Sezione4 from "./Sezione4.vue";
import Sezione5 from "./Sezione5.vue";
import Sezione6 from "./Sezione6.vue";
import Sezione7 from "./Sezione7.vue";
import Sezione8 from "./Sezione8.vue";
export default {
  components: {
    Sezione1,
    Sezione2,
    Sezione3,
    Sezione4,
    Sezione5,
    Sezione6,
    Sezione7,
    Sezione8,
  },
};
</script>

<style lang="scss">
.p-section {
  text-align: center;
  font-size: 35px;
  margin-top: 4rem;
  margin-bottom: -10rem;
}
</style>