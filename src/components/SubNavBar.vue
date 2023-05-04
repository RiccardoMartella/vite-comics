<script>

import CardsComp from '../components/CardsComp.vue';

export default{
    name: "SubNavBar",
    data() {
        return {};
      },
      components: { 
        CardsComp,
     }
}

</script>

<template>
  <div class="contenitore-sfondo">
    <div>
      <h1>COURRENT SERIES</h1>
    </div>
  </div>
  <div>
    <CardsComp/>
  </div>
</template>
  

<style >

    
</style>

<style scoped lang="scss">
  .contenitore-sfondo{
    background-image:url(../assets/img/jumbotron.jpg);
    height: 42%;
    position: relative;
     div{
      background-color: rgb(95, 99, 255);
      width: 300px;
      position: absolute;
      left:320px;
      top: 355px;
     }
    h1{
      color: white;
      width: 67%;
      margin: auto;
      font-size: 20px;
      padding: 5px;
    }
  }
</style>
