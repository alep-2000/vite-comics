<script>
import HeaderVue from './components/Header.vue'
import JumbotronVue from './components/Jumbotron.vue'
import MainVue from './components/Main.vue'
import FooterVue from './components/Footer.vue'

export default {
  components: {
    HeaderVue,
    JumbotronVue,
    MainVue,
    FooterVue
  }
}
</script>

<template lang="">
  <div>
    <HeaderVue />
    <JumbotronVue />
    <MainVue />
    <FooterVue />
  </div>
</template>

<style lang="scss">
@use './styles/generals.scss' as *;
@use './styles/./partials/variables' as *;
</style>
