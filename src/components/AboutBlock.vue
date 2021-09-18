<template>
    <div class="aboutBlock">
        <div class="name">
          <h3>Trafim Bylinskiy</h3>
          <h4>Front-End developer</h4>
        </div>
        <hr />
        <div class="summary">
          <p>
            I’m a beginner in front-end. I’ve decided to become a front-end dev
            on my third year in the university. My goal is to learn as much as
            possible to be proud of things I do. It’s not about prestige or
            something like that, front-end is something inspiring, kind of art,
            where you can create beautiful and useful applications and every
            time you will learn a lot of new information. So, my goal is to do
            my best.
          </p>
        </div>
        <div class="generalInf">
          <div class="col1">
            <p>
              <i class="fas fa-map-marker-alt"></i
              ><span>Minsk/Soligorsk, Belarus</span>
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
        <div class="skills">
          <i class="fab fa-vuejs"></i>
          <i class="fab fa-js"></i>
          <i class="fab fa-css3-alt"></i>
          <i class="fab fa-html5"></i>
        </div>
      </div>
</template>

<style scoped>
.aboutBlock {
  width: calc(50vw - 260px - 7%);
}
.name {
  margin-left: 2%;
}
h3 {
  font-size: 24px;
  letter-spacing: 1px;
  margin-bottom: 3px;
}
h4 {
  margin: 0;
  font-size: 16px;
  letter-spacing: 0.5px;
  color: #6a6969;
}

hr {
  border: none;
  color: #dddddd;
  background-color: #dddddd;
  height: 1px;
}
.generalInf {
  display: flex;
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

.fa-html5 {
  color: coral;
}
.fa-css3-alt {
  color: darkblue;
}
.fa-js {
  color: goldenrod;
}
.fa-vuejs {
  color: green;
}
.skills .fab {
  margin-right: 5%;
}
.skills {
  font-size: 250%;
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
</style>