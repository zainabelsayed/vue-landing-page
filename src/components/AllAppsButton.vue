<template>
  <button :style="{backgroundColor: color}" class="btn">
    <div class="d-flex justify-content-center align-items-center">
      <p class="m-0">{{text}}</p>
      <figure class="p-0 m-0">
          <img src="../assets/arrow.gif" alt="" class="w-100">
      </figure>
    </div>
  </button>
</template>

<script>
export default {
  name: "AllAppsButton",
  props:{
    color: String,
    text:String
  }
};
</script>
<style scoped>
    button{
        padding: 0.97rem 3.71rem; 
        border-radius: 0.625rem;  
    }
    p{
        font-size: 1.125rem;
        font-weight: 700;
        color: #FDB515;
        padding-left: 0.726rem;
    }
    figure{
        width: 2.03rem;
        height: 1.23rem;
        transform: rotate(90deg);
    }
</style>