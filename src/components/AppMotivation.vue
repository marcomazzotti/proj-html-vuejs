<script>
export default{
  name: "AppMotivation",
  data(){
    return{

    }
  }
}
</script>

<template>
  <div class="wrapper">
    <div class="ms-container text-center">  
      <h2>"I've failed over and over again in my life. and that is why i succeed."</h2>
      <i class="arrow fa-solid fa-chevron-up arrow"></i>
      <i class="arrow fa-solid fa-chevron-up arrow"></i>
      <i class="arrow fa-solid fa-chevron-up arrow"></i>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad illo, laudantium, beatae esse sint alias quos sunt at sequi obcaecati exercitationem nulla suscipit consequatur quidem laboriosam labore nam, fugiat voluptates.</p>
      <button>Buy Avada today <i class="fa-solid fa-chevron-right"></i></button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .wrapper{
    background-image: url("../assets/images/banner2-2x.jpg");
    background-size: cover;
    color: white;
    padding: 7rem 0;
    .ms-container{
      width: 50%;
      margin: 0 auto;
      .arrow{
        color: yellow;
        margin: -2px;
      }
      p{
        color: lightgray;
      }
      button{
        border: none;
        background-color: #4154ff;
        padding: 0.5rem 2rem;
        border-radius: 20px;
        color: white;
      }
    }
  }
</style>