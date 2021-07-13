<template>
<div class="container">
    <img :src="thumb" alt="img">
    <h3>{{title}}</h3>
    <h4>{{price}}</h4>
    <h4>{{type}}</h4>
</div>
</template>

<script>
export default {
    name: "Card",
    props: {
        thumb: String,
        price: String,
        title: String,
        type: String,
    },
}
</script>

<style lang="scss" scoped>

    .container {
        width: calc(100% / 6);

        img {
            padding: 20px;
        }
    }

</style>