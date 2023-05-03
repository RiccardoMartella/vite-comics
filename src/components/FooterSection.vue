<script>

export default{
    name: "FooterSection",
    data() {
        return {
            
        }
    }
}

</script>

<template>
    <footer>
        <div class="contenitore">
            <div>
               <button>SIGN-UP NOW!</button>
            </div>
            <div class="d-flex">
               <h2>FOLLOW US</h2>
               <img src="../assets/img/footer-facebook.png" alt="">
               <img src="../assets/img/footer-periscope.png" alt="">
               <img src="../assets/img/footer-pinterest.png" alt="">
               <img src="../assets/img/footer-twitter.png" alt="">
               <img src="../assets/img/footer-youtube.png" alt="">
            </div>
        </div>          
    </footer>
</template>
  
<style lang="scss">
    footer{
        display: flex;
        align-items: center;
        height: 10%;
        background-color: rgb(43, 43, 43);
    }

    .contenitore {
        width: 63%;
        margin: auto;
        display: flex;
        justify-content: space-between;
    }

    .d-flex {
        display: flex;
        align-items: center;

        img {
            margin: 4px;
            height: 25px;
        }
    }

    h2{
        color: rgb(95, 99, 255);
        margin-right: 10px;
    }
</style>
   