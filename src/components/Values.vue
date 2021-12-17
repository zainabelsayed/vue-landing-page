<template>
  <div class="values d-flex">
      <div class="values__features">
        <h3>كل ما تحتاجه لنمو متجرك في مكان واحد</h3>
        <p class="w-100">
          مميزات سوق تطبيقات زد تساعدك في سهولة وسرعة الاستفادة من خدمات و حلول
          سوق التطبيقات لنمو متجرك و مضاعفة أرباحك
        </p>
        <ValuesFeatures/>
      </div>
    <ValuesPromo/>
  </div>
</template>

<script>
import ValuesFeatures from './ValuesFeatures.vue'
import ValuesPromo from './ValuesPromo.vue'

export default {
  name: "Values",
  components:{
      ValuesFeatures,
      ValuesPromo,
  },
};
</script>
<style scoped>
.values {
  background-color: #fafafc;
  padding-top: 3.93rem;
}
h3 {
  font-size: 1.5rem;
  font-weight: 700;
  color: #8d5da7;
}
p{
    padding-top: 1.28rem;
    font-weight: 400;
    font-size: 1rem;
}
.values__features{
    width: 45%;
    padding-right: 6.687rem;
}

</style>