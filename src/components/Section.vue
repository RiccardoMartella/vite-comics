<script>

export default{
    name: "Section",
    data() {
        return {
            
        }
    }
}

</script>

<template>
    <div>
      <ul>
        <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>DIGITAL COMICS</span></li>
        <li><img src="../assets/img/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span></li>
        <li><img src="../assets/img/buy-comics-shop-locator.png" alt=""><span>SUBSCRIPTION</span></li>
        <li><img src="../assets/img/buy-comics-subscriptions.png" alt=""><span>COMIC SHOP LOCATOR</span></li>
        <li><img src="../assets/img/buy-dc-power-visa.svg" alt=""><SPan>DC POWER VISA</SPan></li>
      </ul>
    </div>
</template>
  

<style >

    
</style>

<style scoped lang="scss">
  div{
    display: flex;
    background-color:rgb(95, 99, 255);
    height:15% ;
    ul{
      width: 70%;
      margin: auto;
      display: flex;
      justify-content: space-around;
      li{
         display: flex;
         align-items: center;
         list-style: none;
         img{
           height: 65px;
           margin-right: 10px;
       }
      }
    }
 }
 
 span{
  color: white;
 }    

</style>