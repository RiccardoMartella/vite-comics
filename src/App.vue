<script>
import NavBar from './components/NavBar.vue';
import SubNavBar from './components/SubNavBar.vue'
import Section from './components/Section.vue'
import SecondSection from './components/SecondSection.vue'
import FooterSection from './components/FooterSection.vue'

export default{
    name: "AppVue",
    data() {
        return {};
    },
    components: { 
      NavBar,
      SubNavBar,
      Section,
      SecondSection,
      FooterSection,
     }
}
</script>


<template>
  <div id="contenitore">
    <NavBar />
    <SubNavBar />
    <Section />
    <SecondSection />
    <FooterSection />
  </div>
</template>

<style lang="scss">
  @use './style/main.scss';

  #contenitore {
    height: 100vh;
  }
</style>
