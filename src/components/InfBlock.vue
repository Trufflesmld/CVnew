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
  background-color: white;
  display: flex;
  justify-content: center;
  align-items: center;
}
.infBlock {
  display: flex;
  height: 55vh;
  width: 50vw;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
}

@media screen and (max-width: 1400px) {
  .infBlock {
    width: 70vw;
  }
  .aboutBlock {
    width: calc(70vw - 260px - 7%);
  }
}

@media screen and (max-width: 1024px) {
  .infBlock {
    width: 90vw;
  }
  .aboutBlock {
    width: calc(90vw - 260px - 7%);
  }
}
</style>
