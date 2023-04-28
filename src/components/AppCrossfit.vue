<script>
export default{
  name: "AppCrossfit",
  data(){
    return{

    }
  }
}
</script>

<template>
<div class="wrapper text-center">
  <i class="fa-solid fa-play player"></i>
  <h2 class="my-3">Crossfit workout of the day</h2>
  <h4 class="mb-3">November 15th, 2019</h4>
  <span><a href="">View all videos<i class="fa-solid fa-arrow-right-long mx-2"></i></a></span>
</div>
</template>

<style lang="scss" scoped>
.wrapper{
  padding: 8rem 0;
  background: linear-gradient(125deg, rgba(0, 0, 255, 0.5) 0%, rgba(255, 0, 0, 0.5) 100%), url(../assets/images/banner14-2x.jpg);
  background-size: cover;
  color: white;
}
.player{
  height: 70px;
  width: 70px;
  background-color: white;
  color: #4154fe;
  border-radius: 50%;
  text-align: center;
  line-height: 70px;
  cursor: pointer;
  transition: transform 0.7s;
  &:hover{
    transform: scale(1.2);
  }
}
h2{
  color: white;
}
h4{
  color: yellow;
}
</style>