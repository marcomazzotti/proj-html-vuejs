<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

  export default{
    data() {
        return {
          headerMenu: [
            { 
              text: "Home",
              url: "#",
              current: true,
            },
            {
              text: "Services",
              url: "#",
              current: false,
            },
            {
              text: "About",
              url: "#",
              current: false,
            },
            {
              text: "Videos",
              url: "#",
              current: false,
            },
            {
              text: "Blog",
              url: "#",
              current: false,
            },
            {
              text: "Store",
              url: "#",
              current: false,
            },
          ],
          footerLeft:{
            text: "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reprehenderit molestiae ab, nostrum tenetur similique quis alias quaerat unde esse repellendus, iure corporis, illo in id delectus rem voluptas accusantium autem!",
          },
          footerCenter:["The best protein shake", "Ultimate cardio workout", "New juices availble now", "tips to find training partners", "20 best healthy recipes"],
          footerRight: ["4746 Tipple Road Michigan 48449", "Mobile : 1.800.000.0000", "Email : info@your-company.com"],
        };
    },
    components: { AppHeader, AppMain, AppFooter }
}
</script>

<template>
  <AppHeader :headerMenu="headerMenu"/>
  <AppMain/>
  <AppFooter :footerLeft="footerLeft" :footerCenter="footerCenter" :footerRight="footerRight"/>
</template>

<style lang="scss">
@use "./general.scss"
</style>