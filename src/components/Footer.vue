<template>
    <div class="footer">
        <div class="lists">
            <ul>
                <li>DC Comics</li>

                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <ul>
                <li>Shop</li>

                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>
            <ul>
                <li>DC</li>

                <li>Terms of Use</li>
                <li>Privacy Policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>
            <ul>
                <li>Sites</li>

                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa </li>
            </ul>
        </div>
        <div class="logo-bg">
        </div>
    </div>
</template>
<script>

export default {
    name:"Footer",
}
</script>

<style lang="scss">
    @import "../style/colors.scss";

    .footer{
        background-image:url("../assets/img/footer-bg.jpg");
        padding: 10px 0;

        display: flex;
        justify-content: space-around;
        align-items: center;
        color:white;
    }

    .logo-bg{
        background-image: url("../assets/img/dc-logo-bg.png");
        width: 200px;
        height: 200px;
        background-size: contain;
        background-position: center;
    }

    .lists{
        display: flex;
        justify-content: space-around;
        align-items: baseline;
        flex-wrap: nowrap;
    }
    ul{
        list-style-type: none;
        padding: 10px;
        li{
            color: gray;
            &:first-child{
                font-size: 18px;
                padding: 10px 0;
                color: white;
                font-weight: bold;
                text-transform: uppercase;
            }
        }
    }
</style>