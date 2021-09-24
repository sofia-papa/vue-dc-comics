<template>
      <div>
          <header>
              <a href="">
                  <img src="../assets/images/dc-logo.png" alt="">
              </a>

              <nav>
                  <ul>
                      <li><a href="#">Characters</a></li>
                      <li><a href="#">Comics</a></li>
                      <li><a href="#">Movies</a></li>
                      <li><a href="#">Tv</a></li>
                      <li><a href="#">Games</a></li>
                      <li><a href="#">Collectibles</a></li>
                      <li><a href="#">Videos</a></li>
                      <li><a href="#">Fans</a></li>
                      <li><a href="#">News</a></li>
                      <li><a href="#">Shop</a></li>
                  </ul>
              </nav>
          </header>
      </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

a img{
    display: flex;
}

ul{
    display: flex;
    justify-content: center;
    list-style: none;
}

li a {
    padding: 20px;
    text-decoration: none;
    
}

</style>