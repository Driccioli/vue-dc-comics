<template>
    <div class="header-full">
        <div class="logo-container">
            <img src="../assets/img/dc-logo.png" alt="DC Logo">
        </div>
        <nav>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Collectibles</li>
                    <li>Videos</li>
                    <li>Fans</li>
                    <li>News</li>
                    <li>Shop</li>
                </ul>
        </nav>
    </div>
</template>
<script>

export default {
    name:"Header",
}
</script>

<style lang="scss" scoped>

@import "../style/colors.scss";

    .header-full{
        display: flex;
        align-items: center;
        justify-content: space-around;
        padding-top: 20px;
        padding-bottom: 20px;
    }
    .logo-container{
        width: 60px;
        img{
            width: 100%;
        }
    }
    ul{
        list-style-type: none;
        li{
            font-size: 12px;
            padding: 15px;
            text-transform: uppercase;
            text-align: center;
            display:inline-block;

            &:hover{
                color: $selected;
                border-bottom: 3px solid $selected;
            }
        };
    }
</style>