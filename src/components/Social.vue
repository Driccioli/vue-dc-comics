<template>
    <div>
        <div class="social-media">
            <button>Sign-up Now!</button>
            <div class="social-links">
                Follow Us
                <div class="social-logo">
                    <img src="..\assets\img\footer-facebook.png" alt="Facebook">
                </div>
                <div class="social-logo">
                    <img src="..\assets\img\footer-twitter.png" alt="Twitter">
                </div>
                <div class="social-logo">
                    <img src="..\assets\img\footer-youtube.png" alt="Youtube">
                </div>
                <div class="social-logo">
                    <img src="..\assets\img\footer-pinterest.png" alt="Pinterest">
                </div>
                <div class="social-logo">
                    <img src="..\assets\img\footer-periscope.png" alt="Periscope">
                </div>
            </div>
        </div>
    </div>
</template>
<script>

export default {
    name:"Social",
}
</script>

<style lang="scss">
@import "../style/colors.scss";

.social-media{
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 30px 0;
    

    background: $dark-mode;
    color: white;

    button{
        border: 2px solid $shop;
        background: none;
        color: white;
        text-transform: uppercase;
        font-weight: bold;
        font-size: 20px;
        padding: 15px;
    }

    
}

.social-links{
        display: flex;
        justify-content: space-around;
        align-items: center;
        font-weight: bold;
        color: $shop;
        font-size: 20px;
        text-transform: uppercase;
        .social-logo{
            padding-left:10px;
            &:first-child{
                padding-left: 30px;
            }
        }
}
</style>