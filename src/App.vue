<script>
import MainSection from './components/MainSection.vue';
import HeaderMenu from './components/HeaderMenu.vue';
import FooterList from './components/FooterList.vue';

export default {
  components: {
    MainSection,
    HeaderMenu,
    FooterList
  }
}
</script>

<template>
  <HeaderMenu />
  <MainSection />
  <FooterList />
</template>

<style lang="scss">
@use "./assets/scss/general.scss"
</style>
