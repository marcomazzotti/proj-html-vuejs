<script>
export default {
  name: "AppHeader",
  props: {
    headerMenu: Array
  },
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <header class="d-flex align-items-center">
    <div class="container d-flex justify-content-between align-items-center">
      <div class="header-left">
        <img src="../assets/images/logo.png" alt="">
      </div>
      <div class="header-right d-flex align-items-center">
        <ul class="d-flex">
          <li v-for="(element, index) in headerMenu" :key="index" :class="element.current ? 'active' : ''">
            {{ element.text }}
          </li>
        </ul>
        <span>new</span>
        <button>Schedule a workout</button>
        <i class="fa-solid fa-cart-shopping"></i>
        <i class="fa-solid fa-magnifying-glass"></i>
      </div>
    </div>
  </header>
</template>

<style lang="scss">
  header{
    background-color: black;
    height: 100px;
    ul{
      list-style-type: none;
      color: grey;
      gap: 2rem;
      margin: 0 !important;
      .new{
        background-color: yellow;
        padding: 0.5rem 0.3rem 0.3rem 0.3rem;
        color: black;
      }
      .active{
        color: white;
      }
    }
    span{
      background-color: yellow;
      margin-left: 0.6rem;
      margin-right: 2rem;
      border-radius: 5px;
      padding: 0.3rem;
    }
    button{
      border: none;
      border-radius: 50px;
      padding: 0.5rem 1.5rem;
      background-color: #4154fe;
      color: white;
      &:hover{
        background-color: #ec5a57 !important;
      }
    }
    i{
      color: grey;
      font-size: 1.2rem;
      margin-left: 2rem;
      cursor: pointer;
      &:hover{
      color: white;
      }
    }
  }
</style>