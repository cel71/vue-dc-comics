<template>

    <div class="sfondo">
        <div class="container">
            <div class="inner-container">
                <div>
                    <ul>
                        <li>DC COMICS</li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                       <li><a href="#">Videos</a></li>
                       <li><a href="#">News</a></li>
                    </ul>
                    <ul>
                       <li>SHOP</li>
                       <li><a href="#">Shop DC</a></li>
                       <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>

                <ul>
                    <li>DC</li>
                    <li><a href="#">Term Of Use</a></li>
                    <li><a href="#">Privacy policy (New)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Concact Us</a></li>
                </ul>
            
                <ul>
                    <li>SITES</li>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
        
            </div>

            <div class="linkbar-img">
                <img src="../assets/dc-logo-bg.png" alt="logo-bg">
            </div>
        </div>
    </div>
    
</template>

<script>
export default {
    name: "Linkbar",
}
</script>

<style lang="scss" scoped>

.sfondo {
    background-image: url("../assets/footer-bg.jpg");
    height: 320px;

    .container {
        display: flex;
        justify-content: space-between;

        .inner-container {
            display: flex;
        }
        
        ul {
            list-style: none;
            color: white;
            margin-top: 30px;
            padding-right: 25px;

            li {
                font-size: 12px;
                padding-bottom: 2px;

                &:first-child {
                    font-size: 15px;
                    font-weight: bold;
                    padding-bottom: 20px;
                }

                a {
                    text-decoration: none;
                    color: rgb(149, 149, 149);
                    cursor: pointer;
                }
            }
        }

        .linkbar-img {
            height: 320px;
            overflow: hidden;
            display: flex;
            align-items: center;
            
            img {
                width: 500px;
            }   
        }
    }
}

</style>