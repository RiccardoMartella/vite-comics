<script>
import NavBar from './components/NavBar.vue';
import SubNavBar from './components/SubNavBar.vue'

export default{
    name: "AppVue",
    data() {
        return {};
    },
    components: { 
      NavBar,
      SubNavBar
     }
}
</script>


<template>
    <NavBar />
    <SubNavBar />
</template>

<style lang="scss">
  @use './style/main.scss';
</style>
