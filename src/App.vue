<script>
import NavBar from './components/NavBar.vue';


export default{
    name: "AppVue",
    data() {
        return {};
    },
    components: { NavBar }
}
</script>


<template>
  <div>
    <NavBar />

  </div>
</template>

<style lang="scss">
  @use './style/main.scss';
</style>
