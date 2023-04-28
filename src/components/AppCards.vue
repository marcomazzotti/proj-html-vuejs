<script>
export default {
  name: "AppCards",
  data() {
    return {};
  }
}
</script>

<template>
  <div class="wrapper">
    <div class="container">
      <div class="card-wrapper d-flex justify-content-between">
        <div class="ms-card">
          <div class="text">
            <i class="arrow fa-solid fa-chevron-up"></i>
            <i class="arrow fa-solid fa-chevron-up"></i>
            <i class="arrow fa-solid fa-chevron-up"></i>
            <h5 class="mt-2">Crossfit workout</h5>
            <p>Push your limits</p>
          </div>
        </div>
        <div class="ms-card2">
          <div class="text">
            <i class="arrow fa-solid fa-chevron-up"></i>
            <i class="arrow fa-solid fa-chevron-up"></i>
            <i class="arrow fa-solid fa-chevron-up"></i>
            <h5 class="mt-2">New gym apparel</h5>
            <p>Look good, feel good</p>
          </div>
        </div>
        <div class="ms-card3">
          <div class="text">
            <i class="arrow fa-solid fa-chevron-up"></i>
            <i class="arrow fa-solid fa-chevron-up"></i>
            <i class="arrow fa-solid fa-chevron-up"></i>
            <h5 class="mt-2">Team training</h5>
            <p>Find a partner</p>
          </div>
        </div>
      </div>
      <div class="quote text-center px-5">
        <h3>"How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser"</h3>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <i class="arrow fa-solid fa-chevron-up"></i>
        <div class="author">
          <img src="../assets/images/avatar-1-2x.jpg" alt="">
          <span class="name">Brad Johnson</span>
          <span class="place">Las Vegas</span>
        </div>
        
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@import "../styles/general.scss";
@import "../styles/variables";
  .wrapper{
    background: rgb(15,38,222);
    background: linear-gradient(125deg, blue 0%, red 100%);
    padding-bottom: 6rem;
    color: white;
    position: relative;
    .ms-card{
      background-image: linear-gradient(to top, rgba(0, 0, 0, 0.7) 35%, rgba(0, 0, 0, 0)), url("../assets/images/service6-2x.jpg");
      background-size: cover;
      position: absolute;
      top: -80px;
    }
    .ms-card2{
      background-image: linear-gradient(to top, rgba(0, 0, 0, 0.7) 35%, rgba(0, 0, 0, 0)), url("../assets/images/box1-2x.jpg");
      background-size: cover;
      position: absolute;
      top: -80px;
    }
    .ms-card3{
      background-image: linear-gradient(to top, rgba(0, 0, 0, 0.7) 35%, rgba(0, 0, 0, 0)), url("../assets/images/box3-2x.jpg");
      background-size: cover;
      position: absolute;
      top: -80px;
    }
    .ms-card, .ms-card2, .ms-card3{
      width: calc(100% / 3 - 40px);
      height: 400px;
      border-radius: 10px 10px 30px 10px;
      position: relative;
      transition: transform 0.7s ease;
      &:hover{
        transform: scale(1.2);
      }
      .text{
        position: absolute;
        bottom: 10px;
        left: 30px;
        i{
          margin: -2px;
        }
        p{
          color: yellow;
        }
      }
    }
    .quote{
      i{
        margin: -2px;
        color: yellow;
      }
    }
    .author{
      img{
        border-radius: 50%;
        width: 50px;
      }
      span{
        margin: 0 0.6rem;
      }
      .name{
        font-weight: 500;
      }
      .place{
        color: lightgray;
      }
    }
  }
</style>