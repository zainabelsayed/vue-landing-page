<template>
  <div class="position-relative d-flex flex-column">
      <div class="promo"></div>
    <figure class="dot-pattern">
            <img src="../assets/DotPattern.png" alt="">
        </figure>
    <figure class="ellipse">
            <img src="../assets/Ellipse.png" alt="">
        </figure>
  </div>
</template>

<script>
export default {
  name: "AppPromo",
};
</script>
<style  scoped>
figure {
  padding: 0;
  margin: 0;
}
.promo {
  background-image: url("../assets/product-3.gif");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 52.93rem;
  height: 549.29px;
  border-radius: 2.5rem;
  margin: 0 auto;
  z-index: 10;
}
.ellipse{
    position:absolute;
    top:55%;
    right: 11rem;
}
.dot-pattern{
    position:absolute;
    top:4.5%;
    left: 10rem;
}
</style>
