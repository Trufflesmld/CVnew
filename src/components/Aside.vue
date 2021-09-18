<template>
  <div class="aside">
    <div class="imgWrap">
      <img src="@/assets/avatar.png" alt="avatar" />
    </div>
    <div class="social">
      <a href="https://vk.com/truffles_mld"><i class="fab fa-vk"></i></a>
      <a href="https://www.instagram.com/_truffles_mld/"
        ><i class="fab fa-instagram"></i
      ></a>
      <a href="https://twitter.com/truffles_mld?s=09"
        ><i class="fab fa-twitter"></i
      ></a>
      <a href="https://github.com/Trufflesmld"><i class="fab fa-github"></i></a>
    </div>
  </div>
</template>
<style scoped>
.aside {
  width: 260px;
  margin: 3%;
}
.imgWrap {
  height: 400px;
  width: 260px;
}
.social {
  display: flex;
  justify-content: space-around;
  align-items: center;
  font-size: 36px;
  height: calc(55vh - 400px - 6%);
}
a {
    color: #000;
}
.fa-vk {
    color: cornflowerblue;
}
.fa-instagram {
    color:#c82d8e ;
}
.fa-twitter {
    color:darkblue;
}
img {
  height: 100%;
  width: auto;
  background: linear-gradient(to top, #dddddd, #ffffff 70%);
}
</style>
