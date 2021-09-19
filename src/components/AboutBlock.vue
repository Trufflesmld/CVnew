<template>
  <div class="aboutBlock">
    <Name id="Name" />
    <hr />
    <Summary />
    <GeneralInf />
    <Skills />
    <hr id="SocialBlock" />
    <SocialBlock id="SocialBlock" />
  </div>
</template>

<script>
import Name from "@/components/Name.vue";
import Summary from "@/components/Summary.vue";
import GeneralInf from "@/components/GeneralInf.vue";
import Skills from "@/components/Skills.vue";
import SocialBlock from "@/components/SocialBlock.vue";
export default {
  components: {
    Name,
    Summary,
    GeneralInf,
    Skills,
    SocialBlock,
  },
};
</script>

<style scoped>
.aboutBlock {
  width: calc(50vw - 260px - 7%);
}

#SocialBlock {
  display: none;
}

hr {
  width: 100%;
  border: none;
  color: #dddddd;
  background-color: #dddddd;
  height: 1px;
}

@media screen and (max-width: 1400px) {
  .aboutBlock {
    width: calc(70vw - 260px - 7%);
  }
}

@media screen and (max-width: 1024px) {
  .aboutBlock {
    width: calc(90vw - 260px - 7%);
  }
}
@media screen and (max-width: 768px) {
  .aboutBlock {
    height: 70vh;
    width: 94%;
    margin: 0 3%;
    margin-top: 0;
    display: flex;
    flex-direction: column;
    justify-content:space-evenly;
  }
  #Name {
    display: none;
  }
  #SocialBlock {
    display: flex;
  }
}
</style>
