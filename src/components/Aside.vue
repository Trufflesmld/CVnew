<template>
  <div class="aside">
    <div class="imgWrap">
      <img src="@/assets/avatar.png" alt="avatar" />
    </div>
    <SocialBlock id="SocialBlock"/>
    <Name id="Name"/>
  </div>
</template>

<script>
import SocialBlock from '@/components/SocialBlock.vue'
import Name from "@/components/Name.vue";
export default {
 components: {
   SocialBlock, Name
 }
}
</script>
<style scoped>
#Name {
  display: none;
}
.aside {
  display: block;
  width: 260px;
  margin: 3%;
}
.imgWrap {
  height: 400px;
  width: 260px;
}

img {
  height: 100%;
  width: auto;
  background: linear-gradient(to top, #dddddd, #ffffff 70%);
}

@media screen and (max-width: 768px) {
  img {
    width: auto;
    height: 100%;
  }
  #SocialBlock {
    display: none;
  }
  #Name {
    display: block;
  }
  .aside {
    height: 20vh;
    width: 94%;
    display: flex;
    justify-content:space-evenly;
    margin-bottom: 0;
  }
  .imgWrap {
    height: 100%;
    width: 200px;
  }
}
</style>
