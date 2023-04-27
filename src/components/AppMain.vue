<script>
import AppJumbo from './AppJumbo.vue';
import AppCards from './AppCards.vue';
import AppHealth from './AppHealth.vue';
import AppMailingList from './AppMailingList.vue';
import AppFeatures from './AppFeatures.vue';
import AppArticles from './AppArticles.vue';
import AppMotivation from './AppMotivation.vue';
import AppSponsor from './AppSponsor.vue';
import AppCrossfit from './AppCrossfit.vue';

export default {
    data() {
        return {};
    },
    components: { AppJumbo, AppCards, AppHealth, AppMailingList, AppFeatures, AppArticles, AppMotivation, AppSponsor, AppCrossfit }
}
</script>

<template>
  <AppJumbo/>
  <AppCards/>
  <AppHealth/>
  <AppMailingList/>
  <AppFeatures/>
  <AppArticles/>
  <AppMotivation/>
  <AppSponsor/>
  <AppCrossfit/>
</template>

<style lang="scss">

</style>