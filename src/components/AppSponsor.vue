<script>
export default{
  name: "AppSponsor",
  data(){
    return{

    }
  }
}
</script>

<template>
  <div class="container">
    <div class="card-wrapper d-flex justify-content-between my-5">
      <div class="ms-card text-center my-5">
        <img class="d-block m-auto" src="../assets/images/sponsor-1-2x-200x103.png" alt="">
        <i class="arrow fa-solid fa-chevron-up my-3"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat optio ratione maxime incidunt obcaecati temporibus facilis inventore qui. Pariatur esse obcaecati placeat laboriosam ab ullam iste delectus, impedit blanditiis perferendis.</p>
        <a href="" class="link">
          <span class="me-2">Visit Yoga Studio</span>
          <i class="arrow fa-solid fa-chevron-right arrow"></i>
        </a>
      </div>
      <div class="ms-card text-center my-5">
        <img class="d-block m-auto" src="../assets/images/sponsor-2-2x-200x103.png" alt="">
        <i class="arrow fa-solid fa-chevron-up my-3"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat optio ratione maxime incidunt obcaecati temporibus facilis inventore qui. Pariatur esse obcaecati placeat laboriosam ab ullam iste delectus, impedit blanditiis perferendis.</p>
        <a href="" class="link">
          <span class="me-2">Join Fitness Center</span>
          <i class="arrow fa-solid fa-chevron-right arrow"></i>
        </a>
      </div>
      <div class="ms-card text-center my-5">
        <img class="d-block m-auto" src="../assets/images/sponsor-3-2x-200x103.png" alt="">
        <i class="arrow fa-solid fa-chevron-up my-3"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat optio ratione maxime incidunt obcaecati temporibus facilis inventore qui. Pariatur esse obcaecati placeat laboriosam ab ullam iste delectus, impedit blanditiis perferendis.</p>
        <a href="" class="link">
          <span class="me-2">Learn about FC</span>
          <i class="arrow fa-solid fa-chevron-right arrow"></i>
        </a>
      </div>
      <div class="ms-card text-center my-5">
        <img class="d-block m-auto" src="../assets/images/sponsor-4-2x-200x103.png" alt="">
        <i class="arrow fa-solid fa-chevron-up my-3"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat optio ratione maxime incidunt obcaecati temporibus facilis inventore qui. Pariatur esse obcaecati placeat laboriosam ab ullam iste delectus, impedit blanditiis perferendis.</p>
        <a href="" class="link">
          <span class="me-2">Visit Power Gym</span>
          <i class="arrow fa-solid fa-chevron-right arrow"></i>
        </a>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@import "../styles/general.scss";
@import "../styles/variables";
  .ms-card{
    width: calc(100% / 4 - 60px);
    i{
      color: $main-blue;
      margin: -2px;
    }
    p{
      color: grey;
    }
    a{
      color: inherit;
      font-weight: 500;
      text-decoration: none;
      i{
        color: inherit;
      }
    }
  }
  .link:hover{
      color: #4154ff;
    }
</style>