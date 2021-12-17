<template>
  <div class="text-center">
    <h1>طور متجرك ووسع آفاق تجارتك مع سوق تطبيقات زد</h1>
    <p class="m-auto">
      طور تجارتك من خلال تطبيقات و حلول سوق تطبيقات زد التي تساعدك في نمو أرباحك
      عبر إدارة عمليات متجرك بشكل فعال و احترافي
    </p>
    <AllAppsButton :color="color" :text="text"/>
    <AppPromo/>
  </div>
</template>

<script>
import AllAppsButton from './AllAppsButton.vue'
import AppPromo from './AppPromo.vue'
export default {
  name: "HeroSection",
  components:{
      AllAppsButton,
      AppPromo
  },
  data(){
      return{
          color:"#8D5DA7",
          text: "تصفح التطبيقات",
      }
  }
};
</script>

<style scoped>
h1 {
  font-size: 2.25rem;
  font-weight: 700;
  color: #8d5da7;
}
div {
  padding-top: 4.45rem;
  margin-bottom: 12.677rem;
}
p{
    font-size: 18px;
    font-weight: 400;
    padding-top: 1.3rem;
    width: 32rem;
    padding-bottom: 2.52rem;
}
</style>
