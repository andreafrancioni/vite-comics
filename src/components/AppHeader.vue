<script>
export default {
    name: "AppHeader",
    data() {
        return {
            menuLinks: [
                {
                    text: "CHARACTERS",
                    url: "#characters",
                },
                {
                    text: "COMICS",
                    url: "#comics",
                },
                {
                    text: "MOVIES",
                    url: "#movies",
                },
                {
                    text: "GAMES",
                    url: "#games",
                },
                {
                    text: "COLLECTIBLES",
                    url: "#collectibles",
                },
                {
                    text: "VIDEOS",
                    url: "#videos",
                },
                {
                    text: "FANS",
                    url: "#fans",
                },
                {
                    text: "NEWS",
                    url: "#news",
                },
                {
                    text: "SHOP",
                    url: "#shop",
                },
            ]
        }
    }
}
</script>

<template>
    <header class="bg-white py-2">

        <nav class="container">
            <div class="row">
                <div id="logo" class="col-4 d-flex align-items-center justify-content-center">
                    <img src="../assets/img/dc-logo.png" alt="">
                </div>
                <div id="links" class="col-8 d-flex align-items-center justify-content-end">
                    <a class="mx-3" href="" v-for="link in menuLinks">{{ link.text }}</a>
                </div>
            </div>
        </nav>
    </header>
</template>

<style scoped>
header {
    height: 100px;
}

nav {
    height: 100%;
}

.row {
    height: 100%;
}

img {
    height: 60px;
}

a {
    font-size: 0.8rem;
    font-weight: 600;
    color: rgb(79, 79, 79);
    text-decoration: none;
}
</style>