<script>

export default{
    name: "SecondSection",
    data() {
        return {
            
        }
    }
}

</script>

<template>
    <section>
     <div class="contenitore-generale">
        <div class="prima-lista">
            <ul>
                <h3>DC Comics</h3>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul> 
            <ul class="margin-top">
                <h3>Shop</h3>
                <li>Characters</li>
                <li>Comics</li>
            </ul>
          
        </div>

        <ul>
            <h3>DC </h3>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
        </ul>

        <ul>
            <h3>Sites</h3>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>         
        </ul>
        <div class="overflow">
            
        </div>
     </div>
    
    </section>
</template>
  

<style >

    
</style>

<style scoped lang="scss">
  section{
    display: flex;
    align-items: center;
    height: 45%;
    background-color: rgb(28, 28, 28);
    background-image: url(../assets/img/footer-bg.jpg);   
    background-size: cover;
    div{
        display: flex; 
       ul{
        list-style: none;
        color: white;
        li{
            margin-top: 3px;
            font-size: 14px;
            color:rgba($color: #fffefe, $alpha: 0.5);
        }
      } 
    }
 }

 ul{
    h3{
        margin-top: 30px;
    }
 }

 section{
    overflow: hidden;
 }
 .contenitore-generale{
    width: 67%;
    margin: auto;
 }

.prima-lista{
    flex-direction: column;
}

.margin-top{
    margin-top: 5px;
}

.overflow{
    width: 100%;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: 70%;
    background-position: center right;
}
</style>