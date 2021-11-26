<template>
  <div>
    <Sezione1 />
    <Sezione2 />

    <p class="p-critics">What critics are saying about us</p>

    <Sezione3 />
  </div>
</template>

<script>
import Sezione1 from "./Sezione1.vue";
import Sezione2 from "./Sezione2.vue";
import Sezione3 from "./Sezione3.vue";
export default {
  components: {
    Sezione1,
    Sezione2,
    Sezione3,
  },
};
</script>

<style lang="scss">
.p-critics {
  text-align: center;
  font-size: 35px;
  margin-top: 4rem;
  margin-bottom: -10rem;
}
</style>