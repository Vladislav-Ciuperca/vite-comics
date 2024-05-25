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
    <div class="mine-bg-darkGrey p-4">
        <div class="container-lg d-flex justify-content-between">
            <input type="button" value="SIGN-UP NOW!">
            <div class="contacts d-flex align-items-center">
                <span>FOLLOW US</span>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>

<style scoped>
.mine-bg-darkGrey {
    background: #2E2E2E;
}

input {
    border: 2px solid #0282F9;
    padding: 10px 15px;
    background: none;
    color: white;
}

.contacts * {
    padding: 0 1rem;

}

span {
    color: #0282F9;
    font-weight: 500;
    font-size: 20px;
}
</style>