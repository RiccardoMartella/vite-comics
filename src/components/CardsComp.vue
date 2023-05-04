<script>

export default{
    name: "CardsComp",
    data() {
        return {
            Cards :[
               {
                 "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                 "price": "$19.99",
                 "series": "Action Comics",
                 "type": "comic book"
               },
               {
                 "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                 "price": "$3.99",
                 "series": "American Vampire 1976",
                 "type": "comic book"
               },
               {
                 "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                 "price": "$16.99",
                 "series": "Aquaman",
                 "type": "graphic novel"
               },
               {
                 "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
                 "price": "$2.99",
                 "series": "Batgirl",
                 "type": "comic book"
               },
               {
                 "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                 "price": "$3.99",
                 "series": "Batman",
                 "type": "comic book"
               },
               {
                 "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                 "price": "$2.99",
                 "series": "Batman Beyond",
                 "type": "comic book"
               },
               {
                 "thumb":"https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                 "price": "$3.99",
                 "series": "Batman/Superman",
                 "type": "comic book"
               },
               {
                 "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                 "price": "$4.99",
                 "series": "Batman/Superman Annual",
                 "type": "comic book"
               },
               {
                 "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                 "price": "$5.99",
                 "series": "Batman: The Joker War Zone",
                 "type": "comic book"
               },
               {
                 "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                 "price": "$6.99",
                 "series": "Batman: Three Jokers",
                 "type": "comic book"
               },
               {
                 "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                 "price": "$4.99",
                 "series": "Batman: White Knight Presents: Harley Quinn",
                 "type": "comic book"
               },
               {
                 "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                 "price": "$16.99",
                 "series": "Catwoman",
                 "type": "graphic novel"
               }
            ]
        }
    }
}

</script>

<template>
    <div>
        <div class="contenitore-margin">
           <div class="contenitore-cards" v-for="(element,index) in Cards" :key="index">
             <img v-bind:src="element.thumb" alt="">
             {{ element.price }}
            </div>
        </div>
    </div>
</template>
  



<style scoped lang="scss">
   div{
     display: flex;
     flex-wrap: wrap;
     gap:10px;
     background-color: rgb(18, 18, 18);
   }

   .contenitore-margin{
      
      width: 67%;
      margin: auto;
      padding: 40px 0;
    }
   
   .contenitore-cards{
      display: flex;
      flex-direction: column;
      align-items: center;
      width: calc(100% / 6 - 10px);
   }

   img{
    height: 180px;
   }
</style>
