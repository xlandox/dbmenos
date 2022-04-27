<template>
  <NavMenu/>
  <FormMenu/>
  <QuienesMenu/>
  <GradMenu/>
  <PrenMenu/>
  <ContactMenu/>
  <FooterMenu/>
</template>

<script>
import NavMenu from './components/NavMenu.vue'
import FormMenu from './components/FormMenu.vue'
import QuienesMenu from './components/QuienesMenu.vue'
import GradMenu from './components/GradMenu.vue'
import PrenMenu from './components/PrenMenu.vue'
import ContactMenu from './components/ContactMenu.vue'
import FooterMenu from './components/FooterMenu.vue'

export default {
  name: 'App',
  components: {
    NavMenu,
    FormMenu,
    QuienesMenu,
    GradMenu,
    PrenMenu,
    ContactMenu,
    FooterMenu
  }
}
</script>

<style scoped>
  @import './assets/font-family/fonts.css';
  body{
    font-family: "CocoGothic";
  }
</style>


