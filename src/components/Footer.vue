<template>

<div class="sfondo">
    <div class="container">
        <button>SIGN-UP NOW!</button>
        <div class="social-icons">
            <div>FOLLOW US</div>
            <img src="../assets/footer-facebook.png" alt="facebook">
            <img src="../assets/footer-twitter.png" alt="twitter">
            <img src="../assets/footer-youtube.png" alt="youtube">
            <img src="../assets/footer-pinterest.png" alt="pinterest">
            <img src="../assets/footer-periscope.png" alt="periscope">
        </div>
    </div>
</div>
    
</template>

<script>
export default {
    name: "Footer",
}
</script>

<style lang="scss" scoped>

.sfondo {
    background-color: rgb(48, 48, 48);
    margin-bottom: 30px;

    .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 25px 0;

        button {
            padding: 15px;
            border: 2px solid rgb(2, 130, 249);
            background-color: rgb(48, 48, 48);
            color: white;
            font-weight: bold;

            &:hover {
                cursor: pointer;
            }
        }

        .social-icons {
            display: flex;
            align-items: center;

            div {
                color:rgb(2, 130, 249);
                font-weight: bold;
                padding-right: 15px;
            }

            img {
                padding: 0 10px;

                &:hover {
                    cursor: pointer;
                }
            }
        }
    }
}

</style>