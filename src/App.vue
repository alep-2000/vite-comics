<script>
import HeaderVue from './components/Header.vue'
import MainVue from './components/Main.vue'
import FooterVue from './components/Footer.vue'

export default {
  components: {
    HeaderVue,
    MainVue,
    FooterVue
  }
}
</script>

<template lang="">
  <div>
    <HeaderVue />
    <MainVue />
    <FooterVue />
  </div>
</template>

<style lang="scss">
@use './styles/generals.scss' as *;
@use './styles/./partials/variables' as *;
</style>
