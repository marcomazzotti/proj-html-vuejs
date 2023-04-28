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
        <a href=""><img src="../assets/images/logo.png" alt=""></a>
      </div>
      <div class="header-right d-flex align-items-center">
        <ul class="d-flex">
          <li v-for="(item, index) in headerMenu" :key="index" :class="item.current ? 'active' : ''">
            {{ item.text }}
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

<style lang="scss" scoped>
@import "../styles/general.scss";
@import "../styles/variables";

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
      li:hover{
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
      background-color: $main-blue;
      color: white;
      &:hover{
        background-color: red !important;
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