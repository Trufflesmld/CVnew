<template>
  <div class="generalInf">
    <div class="col1">
      <p>
        <i class="fas fa-map-marker-alt"></i
        ><span>Minsk, Belarus</span>
      </p>
      <p><i class="fas fa-university"></i><span>BSUIR</span></p>
      <p><i class="fas fa-birthday-cake"></i><span>23.10.2000</span></p>
    </div>
    <div class="col2">
      <p>
        <i class="fas fa-phone-alt"></i
        ><a href="tel:+375(29)765-82-06">+375(29)765-82-06</a>
      </p>
      <p>
        <i class="fas fa-envelope"></i
        ><a href="mailto:trufflesmld@gmail.com">trufflesmld@gmail.com</a>
      </p>
      <p>
        <i class="fab fa-telegram"></i
        ><a href="https://t.me/Truffles_mld">@Truffles_mld</a>
      </p>
    </div>
  </div>
</template>

<style scoped>
.generalInf {
  display: flex;
  justify-content:space-evenly;
}

.col1 {
  margin-right: 10%;
}

a {
  text-decoration: none;
  color: black;
}
.col1,
.col2 {
  width: 50%;
}
a:hover {
  text-decoration: underline;
}
i {
  margin-right: 3%;
}

@media screen and (max-width: 768px) {
  .col1 {
  margin-right: 0;
}
.generalInf {
  font-size: 0.7em;
}
}
</style>
