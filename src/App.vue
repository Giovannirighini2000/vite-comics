<script>
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'
import AppMain from './components/AppMain.vue'
import AppMainImg from './components/AppMainImg.vue'


export default {
  components: {
    AppHeader,
    AppFooter,
    AppMain,
    AppMainImg,
  }

}
</script>

<template>
  <div>
    <AppHeader />
    <AppMain />
    <AppMainImg />
    <AppFooter />




  </div>
</template>

<style lang="scss">
@use './style/partials/general.scss'
</style>
