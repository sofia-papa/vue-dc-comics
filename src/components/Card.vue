<template>
    <section class="cards-margin"> 
        <div class="serie-box" >
            <img :src= "src" :alt= "title">
        </div>
        <h5 class="title-series">{{ title }}</h5>
    </section>
</template>

<script>
export default {
    name: "card",
    props: {
        title: {
            String,
            required: true,

        },
        src: String,
    }

}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";
@import "../style/general.scss";

.cards.margin h5 {
        font-size: 0.6rem;
   
}

.serie-box{
    height: 150px;
    width: 150px;
    margin: 2px;
    
    img{
        width: 80%;
        height: 150px;
    }

}

</style>