<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-white">
  <div class="app-container d-flex justify-content-center align-items-baseline">
      <a class="navbar-brand" href="#">
          <figure class="m-0 p-0">
              <img src="../assets/zid-logo.png" alt="">
          </figure>
      </a>
    <div>
      <ul class="navbar-nav">
        <li class="nav-item">
          <a aria-current="page" href="#">الرئيسية</a>
        </li>
        <li class="nav-item">
          <a href="#">التصنيفات</a>
        </li>
        <li class="nav-item">
          <a href="#">التطبيقات</a>
        </li>
        <li class="nav-item">
          <a href="#">طور تطبيق</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default({
    name: 'Navbar'
})
</script>
<style scoped>
    .nav-item{
        padding: 0 3.2rem;
    }
    a{
        color:#000000;
        font-weight: 400;
        font-size: 1rem;
        text-decoration: none;
    }
    .app-container{
      padding-right: 8rem;
    }
</style>
