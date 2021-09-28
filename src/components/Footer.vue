<template>
    <div class="bg-image footer-container">
        
        <div class="footer-list">
            
            <nav>
                <ul>
                    <h3>DC COMICS</h3>
                    <li><a href="#">Collectibles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                </ul>

                <h3>SHOP</h3>
                <ul>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                </ul>
            </nav>
        </div>

         <div class="footer-list">
            
            <nav>
                <ul>
                    <h3>DC COMICS</h3>
                    <li><a href="#">Collectibles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                </ul>
            </nav>
        </div>

         <div class="footer-list">
            
            <nav>
                <ul>
                    <h3>DC COMICS</h3>
                    <li><a href="#">Collectibles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                </ul>
            </nav>

            <div class="img-big">
                 <img src="../assets/images/dc-logo-bg.png" alt="">
            </div>
        </div>


    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.bg-image{
    height: 400px;
    background-image: url("../assets/images/footer-bg.jpg");
    background-size: cover;
    background-repeat: no-repeat;
}

.footer-container{
    display: flex;


    .footer-list{
        margin-right: 10px;
        color: $whiteColor;
        display: flex;
    }

ul {
    list-style: none;
}

     li a{
         text-decoration: none;  
         color: $textColor;
        }

.img-big img{ 
    display: flex;
    height: 400px;
}

.sign-up-now{
    background-color: $secondaryColor;
    height: 200px;
}

}


</style>