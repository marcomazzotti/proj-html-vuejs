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
          ]
        };
    },
    components: { AppHeader, AppMain, AppFooter }
}
</script>

<template>
  <AppHeader :headerMenu="headerMenu"/>
  <AppMain/>
  <AppFooter/>
</template>

<style lang="scss">
@use "./general.scss"
</style>