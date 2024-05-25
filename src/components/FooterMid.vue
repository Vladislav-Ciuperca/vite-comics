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
            <div class="sx d-flex ">
                <div class=" debug">
                    <ul v-for="elemento in contenutoFooter[0]">DC COMICS
                        <li v-for="vocie in elemento">{{ vocie }}</li>
                    </ul>
                    <ul v-for="elemento in contenutoFooter[1]">SHOP
                        <li v-for="vocie in elemento">{{ vocie }}</li>
                    </ul>
                </div>
                <div class=" debug">
                    placeholder
                    <!-- <ul v-for="elemento in contenutoFooter[2]">DC COMICS
                        <li v-for="vocie in elemento">{{ vocie }}</li>
                    </ul> -->
                </div>
                <div class=" debug">
                    <div>palcefwsd</div>
                </div>
            </div>
            <div class="dx">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>


<style scoped>
.footer-bg-container {
    background-image: url(../assets/img/footer-bg.jpg);
    height: 28rem;
}

.debug {
    border: 2px dashed green;
    margin-top: 2rem;
    height: 23rem;
    text-wrap: nowrap;
}

ul {
    padding: 0;
    font-weight: 500;
    font-size: 20px;
}

li {
    font-weight: 300;
    font-size: 15px;
    color: #999;
    list-style-type: none;
}

.dx {
    overflow: hidden;
    position: relative;
    height: 28rem;
    width: 40rem;
}

img {
    position: absolute;
    float: right;
    bottom: -85px;
    left: 0px;
    width: 100%;
}
</style>