<template>
    <div id="header" class="d-flex justify-content-between align-items-center">
        <div id="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div id="nav">
            <ul class="d-flex justify-content-between align-items-sm-center">
                <li class="m-1"><a href="#">CHARACTERS</a></li>
                <li class="m-1"><a href="#">COMICS</a></li>
                <li class="m-1"><a href="#">MOVIES</a></li>
                <li class="m-1"><a href="#">TV</a></li>
                <li class="m-1"><a href="#">GAMES</a></li>
                <li class="m-1"><a href="#">COLLECTIBLES</a></li>
                <li class="m-1"><a href="#">VIDEOS</a></li>
                <li class="m-1"><a href="#">FANS</a></li>
                <li class="m-1"><a href="#">NEWS</a></li> 
                <li class="m-1"><a href="#">SHOP</a></li> 
            </ul>
        </div>
    </div>
</template>

<script>
    export default{
        name: 'HeaderComponent',
    };

</script>

<style lang="scss" scoped>
   #header{
        width: 100%;
        height: 90px;
        margin: 0 auto;
        padding-left: 8%;
        padding-right: 8%;
        background-color: white;
        border: 1px solid black;
   }

   #logo img{
        width: 60px;
        height: 60px;
       
    }

    ul{
        list-style: none;
        margin: 0 !important; 
        li {
            padding:0 0.4rem;
            margin-bottom: 0 !important;
            a {
                text-decoration: none;
                color: black;
                text-transform: uppercase;
                height: 78px;
                display: inline-block;
                line-height: 77px;
                border-bottom: 2px solid transparent;
                
                &:hover{
                border-bottom: 3px solid #0066ff;
                color: #0066ff;
                }
            }
            
        }
    }
   
</style>

