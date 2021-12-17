<template>
    <div>
        <div class="app-container">
        <figure class="text-center">
            <img src="../assets/footer-logo.png" alt="">
        </figure>
        <div class="d-flex justify-content-center pb-5 text-center">
        <div class="d-flex justify-content-between text-white social flex-row-reverse">
            <i class="fab fa-youtube"></i>
            <i class="fab fa-linkedin"></i>
            <i class="fab fa-instagram"></i>
            <i class="fab fa-twitter"></i>
        </div>
        </div>
        <div class="d-flex justify-content-between align-items-center">
        <figure class=" p-0">
            <img src="../assets/chat-icon.png" alt="">
        </figure>
        <i class="fas fa-arrow-circle-up icon"></i>
        </div>
        </div>
    </div>
</template>
<script>
export default {
   name:'Footer'
}
</script>
<style scoped>
div{
    background-color: #835D9D;
}
.social{
    width: 13.43rem;
}
.icon{
    color: #FED14A;
    font-size: 3rem;
}
.app-container{
    padding: 1rem  3.75rem 0 3.75rem;
}
</style>