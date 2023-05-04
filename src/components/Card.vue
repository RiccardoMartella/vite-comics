<script>

export default{
    name: "Card",
    data() {
        return { };
    },
    components: { },
    props: {
        cardContent: Object,
    }
}

</script>

<template>
  <div>
    <img v-bind:src="cardContent.thumb" alt="">
    {{ cardContent.price }}
  </div>
</template>
  
<style scoped lang="scss">
    img{
        height: 180px;
    }
</style>
