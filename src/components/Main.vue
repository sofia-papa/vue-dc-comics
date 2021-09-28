<template>
   <div class="color-bg" >
       <section class="main-container"></section>

       <section class="current-series">
            <Card v-for="(serie, index) in products" :key= "index" :title= "serie.series"
             :src= "serie.thumb"/>
       </section>

       <div class="button">Load More</div>
   </div>

</template>

<script>
import Card from "./Card.vue"
import series from "../data/series.js"

export default {
    name: "series",

    components: {
        Card,
    },
    data: function() {
        return {
            products: series,
        }
    }
}

</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.color-bg{
    background-color: $mainColor;
    padding-bottom: 50px;

    .button{
        margin-top: 20px;
        margin-left: 500px;
        width: 100px;
        height: 10px;
        padding: 1rem 2rem;
        background-color: $primaryColor;
        
    }
}

.main-container h2{
    color: $whiteColor;
}

.main-container{
    background-color: $mainColor;
    padding: 10rem 2rem;

    background-image: url("../assets/images/jumbotron.jpg");
    background-size: cover;
    display: flex;

    margin-bottom: 50px;
    
}

.current-series{
    
    display: flex;
    flex-wrap: wrap;

    font-size: 0.8rem;
    margin: 0 150px;
    color: $whiteColor;
    
}
</style>