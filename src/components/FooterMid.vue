<script>
export default {
    data() {
        return {
            contenutoFooter: [
                {
                    content: [
                        'Characters',
                        'Comics',
                        'Movies',
                        'TV',
                        'Games',
                        'Videos',
                        'News',
                    ]
                },
                {
                    content: [
                        'Shop DC',
                        'Shop DC collectibles',
                    ]
                },
                {
                    content: [
                        'Terms Of Use',
                        'Privacy Policy(New)',
                        'Ad Choices',
                        'Advertising',
                        'Jobs',
                        'Subscriptions',
                        'talent Workshop',
                        'CPSC Certificates',
                        'Ratings',
                        'Shop Help',
                        'Contact Us',
                    ]
                },
                {
                    content: [
                        'DC',
                        'MAD magazines',
                        'DC Kids',
                        'DC Universe',
                        'DC Power visa',
                    ]
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
    <div class="footer-bg-container ">
        <div class="container-lg d-flex justify-content-between">
            <!-- parte sinistra -->
            <div class="sx d-flex ">
                <div class=" debug">
                    <ul v-for="elemento in contenutoFooter[0]">DC COMICS
                        <a href="">
                            <li v-for="vocie in elemento">{{ vocie }}</li>
                        </a>
                    </ul>
                    <ul v-for="elemento in contenutoFooter[1]">SHOP
                        <li v-for="vocie in elemento">{{ vocie }}</li>
                    </ul>
                </div>
                <div class=" debug">
                    <ul v-for="elemento in contenutoFooter[2]">DC
                        <li v-for="vocie in elemento">{{ vocie }}</li>
                    </ul>
                </div>
                <div class=" debug">
                    <ul v-for="elemento in contenutoFooter[3]">SITES
                        <li v-for="vocie in elemento">{{ vocie }}</li>
                    </ul>
                </div>
            </div>
            <!-- destra logo  -->
            <div class="dx">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>


<style scoped>
.footer-bg-container {
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 25rem;
}

.debug {
    /* border: 2px dashed green; */
    margin-top: 2rem;
    height: 23rem;
    text-wrap: nowrap;
    margin-right: 1.5rem;
}

ul {
    padding: 0;
    padding-bottom: 9px;
    font-weight: 500;
    font-size: 20px;
}

li {
    font-weight: 400;
    font-size: 15px;
    color: #999;
    list-style-type: none;
    text-decoration: none;
}

.dx {
    overflow: hidden;
    position: relative;
    height: 25rem;
    width: 38rem;
}

img {
    position: absolute;
    float: right;
    bottom: -100px;
    left: 0px;
    width: 100%;
}

a {
    text-decoration: none;
}

li:hover {
    color: aliceblue;
    cursor: pointer;
}
</style>