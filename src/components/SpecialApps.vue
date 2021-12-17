<template>
  <ul class="list-unstyled p-0 row row-cols-4 justify-content-between">
    <li v-for="app in appData" class="p-3 col mb-3" :key="app.id">
      <div class="d-flex justify-content-start align-items-center">
        <figure class="icon">
          <img  v-bind:src="require('../assets/' + app.icon)" alt="" />
        </figure>
        <div>
          <div class="d-flex align-items-baseline">
            <p class="app-name mb-0">{{app.appName}}</p>
            <figure class="p-0 m-0 star">
              <img class="w-100" src="../assets/star.png" alt="" />
            </figure>
            <p class="pe-1 rating mb-0">{{app.rating}}</p>
          </div>
          <p class="mb-0 developer">تطوير:  {{app.developer}}</p>
        </div>
      </div>
      <p class="description">
        {{app.description}}
      </p>
    </li>
  </ul>
</template>
<script>
export default {
  name: "SpecialApps",
  data() {
    return {
      appData: [
        {
          id: 1,
          appName: "قمرة",
          rating: 5,
          icon: "app-name.png",
          description:
            "نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك",
            developer:"عمر برهوم"
        },
         {
          id: 2,
          appName: "قمرة",
          rating: 5,
          icon: "app-name.png",
          description:
            "نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك",
            developer:"عمر برهوم"
        },
         {
          id: 3,
          appName: "قمرة",
          rating: 5,
          icon: "app-name.png",
          description:
            "نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك",
            developer:"عمر برهوم"
        },
         {
          id: 4,
          appName: "قمرة",
          rating: 5,
          icon: "app-name.png",
          description:
            "نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك",
            developer:"عمر برهوم"
        }
      ],
    };
  },
};
</script>
<style scoped>
ul {
  margin-top: 2.54rem;
  margin-bottom: 2.516rem;
}
li {
  width: 295.01px;
  height: 169.67px;
  background-color: #f7f7f7;
  border-radius: 10px;
}
.icon,
p {
  margin-left: 0.5rem;
}
.rating {
  color: #45a787;
  font-weight: 600;
  font-size: 0.875rem;
}
figure {
  margin: 0;
  padding: 0;
}
.star {
  width: 12px;
  height: 12px;
}
.app-name {
  font-weight: 600;
  font-size: 1rem;
}
.developer,
li p {
  font-weight: 400;
  font-size: 0.625rem;
}
.description {
  margin-top: 20.45px;
  margin-right: 3.25rem;
}
</style>