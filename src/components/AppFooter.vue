<script>
export default {
  name: "AppFooter",
  props: {
    footerLeft: Object,
    footerCenter: Array,
    footerRight: Array,
  },
  data() {
    return {};
  }
}
</script>

<template>
<footer>
  <div class="container d-flex justify-content-between align-items-start">
    <div class="left text-center">
      <ul>
        <li><a href=""><img src="../assets/images/logo-200x34.png" alt=""></a></li>
        <li>{{ footerLeft.text }}</li>
      </ul>
      <div class="icons">
        <a href=""><i class="fa-brands fa-facebook-f"></i></a>
        <a href=""><i class="fa-brands fa-twitter"></i></a>
        <a href=""><i class="fa-brands fa-youtube"></i></a>
        <a href=""><i class="fa-brands fa-instagram"></i></a>
        <a href=""><i class="fa-brands fa-linkedin-in"></i></a>
      </div>
    </div>
    <div class="center text-center">
      <ul>
        <li><h6>RECENT POSTS</h6></li>
        <li v-for="(item, index) in footerCenter" :key="index">
          <i class="fa-solid fa-chevron-right d-inline"></i>
          <span>{{ item }}</span>
        </li>
      </ul>
    </div>
    <div class="right text-center">
      <ul>
        <li><h6>CONTACT INFORMATIONS</h6></li>
        <li v-for="(item, index) in footerRight" :key="index">
          <span>{{ item }}</span>
        </li>
      </ul>
    </div>
  </div>
</footer>
</template>

<style lang="scss" scoped>
@import "../styles/general.scss";
@import "../styles/variables";

  footer{
    background-color: black;
    min-height: 500px;
    padding: 6rem 0;
    color: white;
    .left, .center, .right{
      width: calc(100% / 3);
      ul{
        padding: 0;
        list-style-type: none;
        li{
          padding-bottom: 1rem;
        }
      }
    }
    .left{
      p{
        color: grey;
        margin: 2rem 0;
      }
      i{
        color: red;
        padding: 0.3rem;
        margin: 0 auto;
      }
      .icons{
        margin: 0 0 0 2rem;
      }
    }
    .center, .right{
      padding-top: 0.5rem;
    }
}
</style>