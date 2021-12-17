<template>
    <div class="app-container text-center">
        <h3>التطبيقات المتميزة</h3>
        <p>تطبيقات تقدم حلول و خدمات مميزة نوصي بتجربتها</p>
        <SpecialApps/>
        <AllAppsButton :color="color" :text="text"/>
    </div>
</template>
<script>
import SpecialApps from './SpecialApps.vue'
import AllAppsButton from './AllAppsButton.vue'
export default {
   name:'Features',
   components:{
       SpecialApps,
       AllAppsButton
   },
   data(){
       return{
           color:"white",
           text:"جميع التطبيقات"
       }
   }
}
</script>
<style scoped>
div{
    padding-top: 11.988rem;
}
h3{
    font-weight: 600;
    font-size: 1.5rem;
}
p{
    font-weight: 400;
    font-size: 0.875rem;
    padding-top: 0.65rem;
}
.app-container{
    padding:11.988rem 5.136rem 0 5.136rem;
    margin-bottom: 7.47rem;
}
</style>