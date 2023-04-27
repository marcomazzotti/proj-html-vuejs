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
        <i class="arrow fa-solid fa-chevron-up"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        <button><i class="fa-brands fa-youtube"></i>  Visit my YouTube channel</button>
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
  .wrapper{
    padding: 2rem 0 10rem 0;
    color: white;
    background-image: url("../assets/images/slider82x-scaled.jpg");
    background-size: cover;
    position: relative;
    // &:before{
    //   content: "";
    //   position: absolute;
    //   top: 0;
    //   right: 0;
    //   bottom: 0;
    //   left: 0;
    //   background: linear-gradient(to left, transparent 0%, transparent 50%, black 67%, transparent 100%);
    // }
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
      padding: 0.5rem 1.5rem;
      background-color: #4154fe;
      color: white;
      margin-right: 1rem;
      &.buy{
        background-color:transparent;
        border: 1px solid grey;
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
      top: 30%;
      right: 25%;
      cursor: pointer;
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