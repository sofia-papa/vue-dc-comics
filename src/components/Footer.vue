<template>
    <div class="footer-container">
        <div class="box-footer">
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
            </div>


            <div class="img-big">
                 <img src="../assets/images/dc-logo-bg.png" alt="">
            </div>
        </div>

        <div class="last-part-footer">
           <h4>SIGN UP NOW!</h4>
        </div>
        <div>
            <p></p>
            <div id="facebook"></div>
            <div id="twitter"></div>
            <div></div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";
@import "../style/general.scss";

.footer-container{
    height: 400px;
    background-image: url("../assets/images/footer-bg.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    
    .footer-list{
        margin-right: 10px;
        color: $whiteColor;
        display: flex;
       
    }

.box-footer{
    display: flex;
    margin: 0 150px;
}

ul {
    list-style: none;
    margin-left: 10px;
    margin-top: 50px;
}

     li a{
         text-decoration: none;  
         color: $whiteColor;
         font-family: 'Gemunu Libre';
         text-align: left;
         
        }

.img-big img{ 
    display: flex;
    height: 400px;
}

.sign-up-now{
    background-color: $secondaryColor;
    height: 200px;
}

.last-part-footer{
    margin-top: 0;
    height: 100px;
    background-color: $mainColor;
    padding-top: 50px;
    display: flex;

    h4 {
        width: 150px;
        height: 30px;
        border: 1px solid $primaryColor;
        margin-left: 150px;
    p {
        display: flex;
    }

    #facebook{
        display: flex;
        background-image: url("../assets/images/footer-facebook.png");
        color: $whiteColor;
}
        
    }


}

}


</style>