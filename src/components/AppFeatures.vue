<script>
export default {
  name: "AppFeatures",
  data() {
    return {

    }
  }
}
</script>

<template>
  <div class="wrapper">
    <div class="container">
      <div class="card-wrapper d-flex justify-content-between">
        <div class="ms-card text-center">
          <i class="fa-solid fa-stopwatch-20 main-img"></i>
          <h5>Team training</h5>
          <p class="sub">Find a partner</p>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum, magni illum commodi natus facilis, aliquid at repellat nemo nulla repudiandae aspernatur necessitatibus veniam cum! Quo corporis voluptatum aspernatur repudiandae saepe?</p>
          <h6><a href="">Find a partner <i class="fa-solid fa-chevron-right"></i></a></h6>
        </div>
        <div class="ms-card text-center">
          <i class="fa-solid fa-dumbbell main-img"></i>
          <h5>Crossfit workout</h5>
          <p class="sub">Push your limits</p>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum, magni illum commodi natus facilis, aliquid at repellat nemo nulla repudiandae aspernatur necessitatibus veniam cum! Quo corporis voluptatum aspernatur repudiandae saepe?</p>
          <h6><a href="">Learn about Crossfit <i class="fa-solid fa-chevron-right"></i></a></h6>
        </div>
        <div class="ms-card text-center">
          <i class="fa-solid fa-scale-balanced main-img"></i>
          <h5>Weight loss plan</h5>
          <p class="sub">Shed those pounds</p>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum, magni illum commodi natus facilis, aliquid at repellat nemo nulla repudiandae aspernatur necessitatibus veniam cum! Quo corporis voluptatum aspernatur repudiandae saepe?</p>
          <h6><a href="">Schedule a workout <i class="fa-solid fa-chevron-right"></i></a></h6>
        </div>
      </div>
      
    </div>
  </div>
</template>

<style lang="scss" scoped>
.wrapper{
  background-color: black;
  color: white;
  padding: 4rem;
  .ms-card{
    width: calc(100% / 3 - 40px);
    padding: 2rem;
    border: 3px solid #4154ff;
    padding: 4.5rem 2rem;
    .main-img{
      font-size: 4rem;
      margin-bottom: 2rem;
    }
    .sub{
      color: yellow;
    }
    p{
      color: lightgrey;
    }
  }
}
</style>