<template id="app">
  <Header />
  <InfBlock />
</template>

<script>
import InfBlock from "@/components/InfBlock.vue";
import Header from "@/components/Header.vue";
export default {
  components: {
    InfBlock,
    Header,
  },
};
</script>

<style>
#app {
  font-family: "Oswald", sans-serif;
}
</style>
