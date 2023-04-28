<script>
export default {
  data() {
    return {};
  }
}
</script>

<template>
    <div class="wrapper">
      <div class="container">
        <p class="red">Certified fitness professional</p>
        <h1>Take control of your health</h1>
        <i class="arrow fa-solid fa-chevron-up my-4"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        <button class="my-3"><i class="fa-brands fa-youtube"></i>  Visit my YouTube channel</button>
        <button class="buy">Buy Avada today  <i class="fa-solid fa-arrow-right"></i></button>
        <i class="fa-solid fa-play player"></i>
        <div class="demos">
          <span class="d-block">Icon</span>
          <span>Demos</span>
        </div>
        <div class="on-sale">
          <p>$39</p>
          <span>On Sale</span>
        </div>
      </div>
    </div>
</template>

<style lang="scss" scoped>
@import "../styles/general.scss";
@import "../styles/variables";
  .wrapper{
    padding: 2rem 0 12rem 0;
    color: white;
    background: linear-gradient(to right, rgba(0, 0, 0, 1) 35%, rgba(0, 0, 0, 0)),url("../assets/images/slider82x-scaled.jpg");
    background-size: cover;
    .arrow{
      color: yellow;
      margin: -2px;
    }
    p{
      color: grey;
    }
    .red{
      color: red;
    }
    button{
      border: none;
      border-radius: 50px;
      padding: 1rem 2rem;
      background-color: $main-blue;
      color: white;
      margin-right: 1rem;
      &:hover{
        background-color: red;
      }
      &.buy{
        background-color:transparent;
        border: 1px solid grey;
        &:hover{
          background-color: white;
          color: black;
        }
      }
    }
    .player{
      height: 70px;
      width: 70px;
      background-color: white;
      color: #4154fe;
      border-radius: 50%;
      text-align: center;
      line-height: 70px;
      position: absolute;
      top: 25%;
      right: 25%;
      cursor: pointer;
      transition: transform 0.7s;
      &:hover{
        transform: scale(1.2);
      }
    }
    .demos, .on-sale{
      height: 80px;
      width: 80px;
      background-color: white;
      color: grey;
      border-radius: 10px;
      text-align: center;
      padding: 0.3rem;
      position: absolute;
    }
    .demos{
      top: 40px;
      right: 10px;
    }
    .on-sale{
      top: 130px;
      right: 10px;
      p{
        color: green;
        font-size: 2rem;
        margin: 0;
      }
    }
  }
</style>