<script>
export default {
  name: "AppArticles",
  data() {
    return {

    }
  }
}
</script>

<template>
  <div class="container">
    <div class="articles d-flex justify-content-between py-5">
      <h5>Latest articles</h5>
      <h6>Read all articles <i class="fa-solid fa-chevron-right"></i></h6>
    </div>
    <div class="cards-container d-flex justify-content-between">
      <div class="ms-card">
        <img src="../assets/images/blog4-2x-800x515.jpg" alt="">
        <p class="name px-3">The best protein shake</p>
        <p class="subtitle px-3">By admin | November 26th, 2019 | Gym</p>
      </div>
      <div class="ms-card">
        <img src="../assets/images/blog1-2x-1200x773.jpg" alt="">
        <p class="name px-3">Ultimate cardio workout</p>
        <p class="subtitle px-3">By admin | November 26th, 2019 | Gym</p>
      </div>
      <div class="ms-card">
        <img src="../assets/images/blog3-2x-800x515.jpg" alt="">
        <p class="name px-3">New juices available now</p>
        <p class="subtitle px-3">By admin | November 26th, 2019 | Gym</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .container{
    padding-top: 5rem;
    padding-bottom: 5rem;
    .ms-card{
      width: calc(100% / 3 - 40px);
      .name{
        font-weight: 600;
        margin-bottom: 0;
      }
      .subtitle{
        font-weight: 300;
        font-size: 0.8rem;
        margin-top: 0.3rem;
      }
    }
  }
</style>