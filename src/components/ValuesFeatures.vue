<template>
<div>
    <ul class="list-unstyled p-0">
            <li v-for="feature in features" class="d-flex align-items-baseline" :key="feature.id">
                <figure class="icon shadow rounded-circle">
                    <img v-bind:src="require('../assets/' + feature.img)" alt="">
                </figure>
                <p>{{feature.text}}</p>
            </li>
        </ul>
         <AllAppsButton :color="color" :text="text"/>
         </div>
</template>
<script>
import AllAppsButton from './AllAppsButton.vue'
export default {
    name:'ValuesFeatures',
    components:{
        AllAppsButton
    },
    data(){
        return{
            features:[
                {   
                    id:1,
                    text:"سهولة إدارة و تفعيل تطبيقاتك من نفس لوحة تحكم متجرك",
                    img:"easy-icon.png"
                },
                {
                    id:2,
                    text:"دعم فني و تقني متكامل متوفر علي مدار الساعة",
                    img:"supportIcon.png"
                },
                {
                    id:3,
                    text:"أسعار تنافسية مع تجربة مجانية و باقات إشتراك متنوعة",
                    img:"priceIcon.png"
                }
            ],
            color:"#8D5DA7",
          text: "تصفح التطبيقات",
        }
    },
}
</script>
<style scoped>
.icon{
    background-color:white;
    width: 3.125rem;
    height: 3.125rem;
    display: flex;
    align-items: center;
    justify-content: center;
}

ul{
    margin-top: 1.278rem;
    margin-bottom: 2.5rem;
}
li p{
    padding-right: 1rem;
    font-weight: 600;
    font-size: 0.875rem;
    margin-top: 1.26rem;
}
div{
    padding-bottom: 3.94rem;
}
</style>