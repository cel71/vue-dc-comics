<template>
    <div class="container header-box">
        <div class="logo">
            <img src="../assets/dc-logo.png" alt="logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: "Header",
}
</script>

<style lang="scss" scoped>
    
    .header-box {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 15px;

        .logo {

            img {
                width: 60px;
            }
            
            &:hover {
                cursor: pointer;
            }
        }

        nav {

            ul {
                display: flex;
                list-style: none;

                li {
                    padding: 0 15px;
                    cursor: pointer;
                    font-size: 14px;

                    a {
                        color: black;
                        text-decoration: none;
                        border-bottom: 3px solid white;
                        padding-bottom: 35px;

                        &:hover {
                            color:rgb(2, 130, 249);
                            border-bottom: 3px solid rgb(2, 130, 249);
                        }
                    }
                }
            }
        }

    }

</style>