<template>
    
    <div class="sfondo">
        <div class="container">
            <div>Content goes here</div>
        </div>
    </div>

    
</template>

<script>
export default {
    name: "Main",
}
</script>

<style lang="scss" scoped>

.sfondo {
    background-color: black;
    color: white;
    
    .container {
        height: 100px;

        div {
            padding-top: 20px;
        }
    }
}

</style>