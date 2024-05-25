<script>
export default {
    data() {
        return {
            messaggino: 'sonon il figlio'
        }
    },
    methods: {
        // placeholder
    },

    mounted() {
        // placehyolder
    }
}
</script>

<template>
    <div class="mine-bg-blue">
        <div class="container-lg">
            <div class="row d-flex p-5">
                <div class="col-12 d-flex align-items-center justify-content-around">

                    <a href="">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="#">
                        <span>DIGITAL COMICS</span>
                    </a>
                    <a href="">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="#">
                        <span>DC MERCHANDISE</span>
                    </a>
                    <a href="">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="#">
                        <span>SUBSCRIPTION</span>
                    </a>
                    <a href="">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="#">
                        <span>COMIC SHOP LOCATOR</span>
                    </a>
                    <a href="">
                        <img class="img-fix" src="../assets/img/buy-dc-power-visa.svg" alt="#">
                        <span>DC POWER VISA</span>
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.mine-bg-blue {
    background: #0282F9;
}

img {
    height: 60px;
}

.img-fix {
    height: 40px;
}

a {
    text-decoration: none;
    color: white;
    transition: all 150ms;
}

a:hover {
    transform: scale(1.15);
}

span {
    padding-left: 1rem;
    font-weight: 400;
}
</style>