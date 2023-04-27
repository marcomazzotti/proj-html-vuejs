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
          <img src="../assets/images/service6-2x.jpg" alt="">
            <div class="text">
              <i class="arrow fa-solid fa-chevron-up"></i>
              <i class="arrow fa-solid fa-chevron-up"></i>
              <i class="arrow fa-solid fa-chevron-up"></i>
              <h5>Crossfit workout</h5>
              <p>Push your limits</p>
            </div>
        </div>
        <div class="ms-card">
            <img src="../assets/images/box1-2x.jpg" alt="">
              <div class="text">
                <i class="arrow fa-solid fa-chevron-up"></i>
                <i class="arrow fa-solid fa-chevron-up"></i>
                <i class="arrow fa-solid fa-chevron-up"></i>
                <h5>New gym apparel</h5>
                <p>Look good, feel good</p>
              </div>
          </div>
          <div class="ms-card">
            <img src="../assets/images/box3-2x.jpg" alt="">
              <div class="text">
                <i class="arrow fa-solid fa-chevron-up"></i>
                <i class="arrow fa-solid fa-chevron-up"></i>
                <i class="arrow fa-solid fa-chevron-up"></i>
                <h5>Team training</h5>
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
  .wrapper{
    background: rgb(15,38,222);
    background: linear-gradient(125deg, blue 0%, red 100%);
    min-height: 400px;
    margin-top: -70px;
    padding-bottom: 6rem;
    color: white;
    .ms-card{
      margin-bottom: 80px;
      width: calc(100% / 3 - 40px);
      // border: 1px solid black;
      position: relative;
      img{
        max-width: 100%;
        border-radius: 10px 10px 30px 10px;
      }
      h5, i{
        color: white;
      }
      p{
        color: yellow;
      }
      i{
        margin: -2px;
      }
      .text{
        position: absolute;
        bottom: 30px;
        left: 30px;
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