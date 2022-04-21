<template>
    <div class="container">
        <div class="row mt-5">
            <div class="col-12 col-lg-6 justify-content-center text-center">
                <div>
                    <p class="titulo">Descargar la app</p>
                </div>
                <div class="store justify-content-center">
                    <div>
                        <a href="#">
                            <img v-bind:src="require('../assets/logo-appstore.png')" alt="appstore" class="appstore">
                        </a>
                    </div>
                    <div>
                        <a href="#">
                            <img v-bind:src="require('../assets/logo-playstore-min.png')" alt="playstore" class="playstore">
                        </a>
                    </div>
                </div>
            </div>
            <div class="col-12 col-lg-6 justify-content-center text-center">
                <div>
                    <p class="titulo">Siguenos en nuestras redes</p>
                </div>
                <div class="d-flex justify-content-center">
                    <div>
                        <a href="#">
                            <img v-bind:src="require('../assets/whatsapp.png')" alt="whatsapp" class="red">
                        </a>
                    </div>
                    <div>
                        <a href="#">
                            <img v-bind:src="require('../assets/twitter.png')" alt="twitter" class="red">
                        </a>
                    </div>
                    <div>
                        <a href="#">
                            <img v-bind:src="require('../assets/youtube.png')" alt="youtube" class="red">
                        </a>
                    </div>
                    <div>
                        <a href="#">
                            <img v-bind:src="require('../assets/facebook.png')" alt="facebook" class="red">
                        </a>
                    </div>
                    <div>
                        <a href="#">
                            <img v-bind:src="require('../assets/instagram.png')" alt="instagram" class="red">
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
    .container{
        border-top: black 3px solid;
    }
    @media (max-width: 576px){
        p.titulo{
            font-weight: 400;
            font-size: 35px;
        }
        .store{
            display: block;
        }
        .appstore{
            width: 225px;
            height: auto;
        }
        .playstore{
            width: 238px;
            height: auto;
        }
        img.red{
            width: 45px;
            height: auto;
            margin: 0 3px;
        }
    }
    @media (min-width: 992px){
        p.titulo{
            font-weight: 400;
            font-size: 25px;
        }
        .store{
            display: flex;
        }
        .appstore{
            width: 225px;
            height: auto;
        }
        .playstore{
            width: 238px;
            height: auto;
        }
        img.red{
            width: 50px;
            height: auto;
        }
    }
</style>