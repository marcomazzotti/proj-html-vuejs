<script>
export default{
  name: "AppMailingList",
  data(){
    return{

    }
  }
}
</script>

<template>
  <div class="wrapper">
    <div class="container">
      <p>Join our mailing list today</p>
      <h2>Insider offers & flash sales in your inbox every week.</h2>
      <i class="arrow fa-solid fa-chevron-up"></i>
      <i class="arrow fa-solid fa-chevron-up"></i>
      <i class="arrow fa-solid fa-chevron-up"></i>
      <div class="input">
        <input type="text" placeholder="Insert your email ... *">
        <button>Subscribe</button>
      </div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt magnam distinctio in nihil ut laboriosam ratione sint iure.</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .wrapper{
    background-image: linear-gradient(to right, rgba(0, 0, 0, 1) 50%, rgba(0, 0, 0, 0.0)), url("../assets/images/banner1-2x.jpg");
    background-size: cover;
    color: white;
    padding: 4rem 0;
    p:first-child{
      color: red;
    }
    p:last-child{
      color: grey;
    }
    i{
      color: yellow;
      margin: -2px;
      margin-bottom: 2rem;
    }
    input{
      width: 400px;
      border-radius: 20px;
      border: none;
      margin-bottom: 2rem;
      padding: 0.5rem 0;
    }
    ::placeholder{
        padding: 0.7rem;
    }
    button{
      background-color: #4154ff;
      color: white;
      padding: 0.5rem 4rem;
      border-radius: 20px;
      border: 1px solid #4154ff;
      margin-left: 2rem;
    }
  }
</style>