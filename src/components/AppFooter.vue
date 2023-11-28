<script>
export default {
    name: "AppFooter"
}

</script>

<template>
    <section>
        <div class="footerMenu container">

            <div class="row">
                <div class="col-6 d-flex justify-content-center pt-3">
                    <div class="site">
                        <h3>DC COMICS</h3>
                        <ul>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                        </ul>
                    </div>
                    <div class="site">
                        <h3>SHOP</h3>
                        <ul>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                        </ul>
                    </div>
                    <div class="site">
                        <h3>DC</h3>
                        <ul>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                        </ul>
                    </div>
                    <div class="site">
                        <h3>SITES</h3>
                        <ul>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                            <li>Sito</li>
                        </ul>
                    </div>
                </div>
                <div class="col-6">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 400px;
    color: white;
}

.footerMenu {
    height: 100%;
    overflow: hidden;
}

.row {
    height: 100%;
}

img {}

.col-6 {
    height: 100%;
}

li {
    list-style: none;
}

.site {
    padding-left: 10px;
}
</style>