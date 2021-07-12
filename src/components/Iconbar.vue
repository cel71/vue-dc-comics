<template>

    <div class="sfondo">
        <div class="container">
            <div class="icon">
                <img src="../assets/buy-comics-digital-comics.png" alt="buy-comics-digital-comics">
                <div>DIGITAL COMICS</div>
            </div>
            <div class="icon">
                <img src="../assets/buy-comics-merchandise.png" alt="buy-comics-digital-comics">
                <div>DC MERCHANDISE</div>
            </div>
            <div class="icon">
                <img src="../assets/buy-comics-subscriptions.png" alt="buy-comics-digital-comics">
                <div>SUBSCRIPTION</div>
            </div>
            <div class="icon">
                <img src="../assets/buy-comics-shop-locator.png" alt="buy-comics-digital-comics">
                <div>COMIC SHOP LOCATOR</div>
            </div>
            <div class="icon">
                <img src="../assets/buy-dc-power-visa.svg" alt="buy-comics-digital-comics">
                <div>DC POWER VISA</div>
            </div>
        </div>
    </div>
    
</template>

<script>
export default {
    name: "Iconbar",
}
</script>

<style lang="scss" scoped>

.sfondo {
    background-color: rgb(2, 130, 249);

    .container {
        display: flex;
        align-items: center;
        justify-content:flex-end;

        .icon {
            display: flex;
            align-items: center;
            color: white;
            padding: 30px;
            font-size: 12px;

            img {
                padding-right: 15px;
                width: 60px;

                &:hover {
                    cursor: pointer;
                }
            }

            div {

                &:hover {
                    cursor: pointer;
                }
            }
        }
    }
}

</style>