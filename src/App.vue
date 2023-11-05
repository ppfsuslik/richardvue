
<template>
  <div>
    <Header />
    <Intro />
    <Menu />
    <Icon />
    <Statistics />
    <Food/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Intro from "./components/Intro.vue";
import Menu from "./components/Menu.vue";
import Icon from "./components/Icon.vue";
import Statistics from "./components/Statistics.vue";
import Food from "./components/Food.vue";
import Footer from "./components/Footer.vue";

  export default {
    components:{ Header, Intro, Menu, Icon, Statistics, Food, Footer }

  }
</script>

<style lang="scss" scoped>

</style>