<template>
    
    <div class="sfondo">
        <div class="jumbotron">
            <img src="../assets/jumbotron.jpg" alt="jumbotron">
            <div>CURRENT SERIES</div>
        </div>
        <div class="container">
            <Card v-for="(element, index) in comics" :key="index" 
            :thumb="element.thumb" 
            :price="element.price" 
            :title="element.title" 
            :type="element.type"/>
        </div>
        <button>LOAD MORE</button>
    </div>

    
</template>

<script>
import Card from "./Card.vue"
export default {
    name: "Main",
    components: {
        Card,
    },
    props: {
        comics: Array,
    }
}
</script>

<style lang="scss" scoped>

.sfondo {
    background-color: black;
    color: white;

    .jumbotron {
        width: 100%;
        height: 300px;
        overflow: hidden;

        img {
            width: 100%;
        }    
    }
    
    .container {
        display: flex;
        flex-wrap: wrap;

        .thumb {
            padding: 0 12px;
        }
    }
}

</style>