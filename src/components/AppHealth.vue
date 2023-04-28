<script>
export default{
  name: "AppHealth",
  data(){
    return{};
  }
}
</script>

<template>
  <div class="wrapper">
    <div class="d-flex">
      <div class="col-left">
        <img src="../assets/images/service15-2x.jpg" alt="">
        <div class="player">
          <i class="fa-solid fa-play"></i>
        </div>
      </div>
      <div class="col-right">
        <span>Tune up your workouts</span>
        <h2>The best health & fitness advice online</h2>
        <div class="yt d-flex mb-4">
          <div class="logo">
            <img src="../assets/images/unnamed.jpg" alt="">
          </div>
          <div class="info">
            <span class="d-block">ThemeFusion</span>
            <button><i class="fa-brands fa-youtube"></i>  YouTube</button>
            <button class="subscribers">999+</button>
          </div>
        </div>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Hic ratione cum doloremque consequatur ducimus, laudantium sunt! Ea illo eos esse perferendis vel sequi saepe exercitationem quo doloribus quibusdam! Magnam, a.</p>
         <button class="button"><i class="fa-brands fa-youtube"></i>  Visit my YouTube channel</button>
      </div>
    </div>
    <div class="container">
      <div class="playlists d-flex justify-content-between">
        <p>Featured playlists</p>
        <p><a href="">View all videos <i class="fa-solid fa-chevron-right"></i></a></p>
      </div>
      <div class="cards-container d-flex justify-content-between">
        <div class="ms-playlist-card">
          <img src="../assets/images/video2-2x.jpg" alt="">
          <div class="play">
            <i class="fa-solid fa-play"></i>
          </div>
          <p class="text-center name">Thighs & glute workout</p>
          <p class="text-center subtitle">Increase your mobility</p>
        </div>
        <div class="ms-playlist-card">
            <img src="../assets/images/video7-2x.jpg" alt="">
            <div class="play">
              <i class="fa-solid fa-play"></i>
            </div>
            <p class="text-center name">Lift, firm & perk up</p>
            <p class="text-center subtitle">Feel young again</p>
          </div>
          <div class="ms-playlist-card">
            <img src="../assets/images/video9-2x.jpg" alt="">
            <div class="play">
              <i class="fa-solid fa-play"></i>
            </div>
            <p class="text-center name">Slim & trim your waist</p>
            <p class="text-center subtitle">Shed those extra pounds</p>
          </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@import "../styles/general.scss";
@import "../styles/variables";
  .col-left{
    width: 40%;
    margin-top: -30px;
    position: relative;
    img{
      max-width: 100%;
      border-radius: 10px 10px 50px 10px;
    }
    .player{
      height: 70px;
      width: 70px;
      background-color: white;
      color: $main-blue;
      border-radius: 50%;
      text-align: center;
      line-height: 70px;
      position: absolute;
      top: 45%;
      right: 45%;
      cursor: pointer;
      transition: transform 0.7s;
      &:hover{
        transform: scale(1.2);
      }
    }
  }
  .col-right{
    width: 50%;
    padding: 4rem 4rem 0 4rem;
    span{
      color: blue;
      font-size: 1.3rem;
    }
    h2{
      margin: 2rem 0;
    }
    p{
      color: grey;
    }
    .button{
      border: none;
      border-radius: 50px;
      padding: 0.5rem 1.5rem;
      background-color: red;
      color: white;
      margin-top: 2rem;
      &:hover{
        background-color: $main-blue;
      }
    }
    .info{
      span{
        font-size: 0.8rem;
        color: grey;
      }
      button{
        background-color: red;
        border: none;
        color: white;
        font-size: 0.8rem;
        border: 1px solid red;
        &:hover{
          background-color: $main-blue;
          border: 1px solid $main-blue;
        }
      }
      .subscribers{
        background-color: #fafafa;
        color: grey;
        border: 1px solid lightgrey;
        &:hover{
          background-color: #fafafa;
          border: 1px solid lightgray;
        }
      }
    }
  }
  .playlists{
    margin: 4rem 0 2rem 0;
    p{
      font-size: 1.2rem;
    }
  }
  .ms-playlist-card{
      width: calc(100% / 3 - 40px);
      position: relative;
      margin-bottom: 6rem;
      transition: transform 0.7s ease;
      img{
        border-radius: 10px 10px 50px 10px;
      }
      &:hover{
        transform: scale(1.2);
      }
      .play{
      height: 50px;
      width: 50px;
      background-color: white;
      color: $main-blue;
      border-radius: 50%;
      text-align: center;
      line-height: 50px;
      position: absolute;
      top: 30%;
      right: 45%;
      cursor: pointer;
      font-size: 0.7rem;
      transition: transform 0.7s;
      &:hover{
        transform: scale(1.2);
      }
    }
    .name{
      margin-top: 2rem;
      font-weight: 500;
      font-size: 1.2rem;
    }
    .subtitle{
      color: $main-blue;
      font-size: 0.8rem;
    }
  }
</style>
