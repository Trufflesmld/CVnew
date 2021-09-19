<template>
  <div class="infWrap">
    <div class="infBlock">
      <Aside />
      <AboutBlock />
    </div>
  </div>
</template>

<script>
import Aside from "@/components/Aside.vue";
import AboutBlock from "@/components/AboutBlock.vue";
export default {
  components: {
    Aside,
    AboutBlock,
  },
};
</script>

<style scoped>
.infWrap {
  height: 100vh;
  background: url(../assets/wrap.jpg);
  display: flex;
  justify-content: center;
  align-items: center;

  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-color: #464646;
}
.infBlock {
  display: flex;
  height: 55vh;
  width: 50vw;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  background-color: white;
}

@media screen and (max-width: 1400px) {
  .infBlock {
    width: 70vw;
  }
}

@media screen and (max-width: 1024px) {
  .infBlock {
    width: 90vw;
  }
}
</style>
