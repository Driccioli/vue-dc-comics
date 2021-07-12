<template>
    <div class="shop-banner">
        <div class="shop-item">
            <div class="shop-icon">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital comics">
            </div>
            
            Digital comics
        </div>
        <div class="shop-item">
            <div class="shop-icon">
                <img src="../assets/img/buy-comics-merchandise.png" alt="Merchandise">
            </div>
            DC Merchandise
        </div>
        <div class="shop-item">
            <div class="shop-icon">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscription">
            </div>
            Subscription
        </div>
        <div class="shop-item">
            <div class="shop-icon">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="Locator">
            </div>
            Comic Shop Locator
        </div>
        <div class="shop-item">
            <div class="shop-icon">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="Visa">
            </div>
            DC Power Visa
        </div>
    </div>
</template>
<script>

export default {
    name:"Shop",
}
</script>

<style lang="scss">

@import "../style/colors.scss";

    .shop-banner{
        background: $shop;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        text-transform: uppercase;
        padding: 50px 20px;
    }

    .shop-item{
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-size: 14px;
        padding-inline: 15px;
        .shop-icon{
            max-width: 40px;
            margin-right: 10px;
            img{
                width: 100%;
                height: 100%;
            }
        }
    }

</style>