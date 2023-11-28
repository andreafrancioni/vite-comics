<script>
export default {
    name: "AppIcons",
    data() {
        return {

        }
    }
}

</script>

<template>
    <section class="bg-banner">
        <div class="comicsCards d-flex justify-content-center align-items-center">
            <div class="comicsCard">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="comicsCard">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>
            <div class="comicsCard">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>SHOP LOCATOR</span>
            </div>
            <div class="comicsCard">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div class="comicsCard">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>POWER VISA</span>
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    color: white;
    height: 100px;
}

.comicsCard {
    margin: 0 1rem;
}

.comicsCards {
    height: 100%;
}

.bg-banner {
    background-color: #0082F9;
}

img {
    width: 40px;
}
</style>