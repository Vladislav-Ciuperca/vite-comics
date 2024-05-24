<script>
export default {
    data() {
        return {
            hedaerLinks: [
                {
                    nome: "CHARACTERS",
                    url: "#characters"
                },
                {
                    nome: " COMICS",
                    url: "#characters"
                },
                {
                    nome: "MOVIES",
                    url: "#characters"
                },
                {
                    nome: "TV",
                    url: "#characters"
                },
                {
                    nome: "GAMES",
                    url: "#characters"
                },
                {
                    nome: "COLLECTABLES",
                    url: "#characters"
                },
                {
                    nome: "VIDEOS",
                    url: "#characters"
                },
                {
                    nome: "FANS",
                    url: "#characters"
                },
                {
                    nome: "NEWS",
                    url: "#characters"
                },
                {
                    nome: "SHOP",
                    url: "#characters"
                },

            ]
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
    <div class="bg-white">
        <div class="container-lg">
            <div class="row">
                <header class="d-flex justify-content-between align-items-center">
                    <img src="../assets/img/dc-logo.png" alt="">
                    <div class="header-dx d-flex">
                        <a class="flex-end" v-for="link in hedaerLinks" href="">{{ link.nome }}</a>
                    </div>
                </header>
            </div>
        </div>
    </div>

</template>

<style scoped>
a {
    padding: 1.5rem;
    color: #635D60;
    text-decoration: none;
    font-weight: 700;
    font-size: 13px;
}

a:hover {
    text-underline-offset: 53px;
    text-decoration: underline;
    text-decoration-thickness: 5px;
    color: #027CED;
}

.header-dx {
    height: 5rem;
}

img {
    width: 80px;
    margin: 1rem 0;
}
</style>