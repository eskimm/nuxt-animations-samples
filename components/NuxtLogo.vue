<template>
  <div class="NuxtLogo">
    <div class="Triangle Triangle--two"/>
    <div class="Triangle Triangle--one"/>
    <div class="Triangle Triangle--three"/>
    <div class="Triangle Triangle--four"/>
  </div>
</template>

<style>
/* stylelint-disable */
.NuxtLogo {
  position: relative;
  overflow: hidden;
  display: inline-block;
  width: 245px;
  height: 180px;
}

.Triangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 0;
  height: 0;
}

.Triangle--one {
  border-left: 105px solid transparent;
  border-right: 105px solid transparent;
  border-bottom: 180px solid #41b883;
}

.Triangle--two {
  top: 30px;
  left: 70px;
  border-right: 87.5px solid transparent;
  border-bottom: 150px solid #3b8070;
  border-left: 87.5px solid transparent;
  animation: goright 0.5s linear forwards 3.5s;
}

.Triangle--three {
  top: 60px;
  left: 70px;
  border-left: 70px solid transparent;
  border-right: 70px solid transparent;
  border-bottom: 120px solid #35495e;
}

.Triangle--four {
  top: 180px;
  left: 70px;
  border-left: 35px solid transparent;
  border-right: 35px solid transparent;
  border-bottom: 60px solid #fff;
}

@media screen and (prefers-reduced-motion: reduce) {
  .Triangle--two {
    top: 30px;
    left: 70px;
    border-right: 87.5px solid transparent;
    border-bottom: 150px solid #3b8070;
    border-left: 87.5px solid transparent;
    animation: none;
  }
}
/* stylelint-enable */
</style>
