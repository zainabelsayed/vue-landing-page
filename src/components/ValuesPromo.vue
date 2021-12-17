<template>
<div class="promo-container">
    <div class="position-relative d-flex flex-column">
      <div class="promo"></div>
    <figure class="dot-pattern">
            <img src="../assets/DotPattern.png" alt="">
        </figure>
    <figure class="ellipse">
            <img src="../assets/Ellipse.png" alt="">
        </figure>
  </div>
  </div>
</template>
<script>
export default {
  name: "ValuesPromo",
};
</script>
<style  scoped>
figure {
  padding: 0;
  margin: 0;
}
.promo {
  background-image: url("../assets/1-min.gif");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 43.81rem;
  height: 441px;
  border-radius: 2.5rem;
  margin: 0 auto;
  z-index: 10;
}
.ellipse{
    position:absolute;
    top:40%;
    right: -3rem;
}
.dot-pattern{
    position:absolute;
    top:-9%;
    left: -1rem;
}
.promo-container{
  width:55%
}
</style>
