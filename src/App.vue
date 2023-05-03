<script>
import NavBar from './components/NavBar.vue';
import SubNavBar from './components/SubNavBar.vue'
import Section from './components/Section.vue'

export default{
    name: "AppVue",
    data() {
        return {};
    },
    components: { 
      NavBar,
      SubNavBar,
      Section,
     }
}
</script>


<template>
    <NavBar />
    <SubNavBar />
    <Section />
</template>

<style lang="scss">
  @use './style/main.scss';
</style>
