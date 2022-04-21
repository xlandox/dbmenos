<template>
    <div class="container-fluid mt-5">
        <div class="text-center pt-5">
            <h1 class="mb-5">Nuestros graduados</h1>
        </div>
        <div class="row">
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/1.png')" alt="1" class="comentario">
            </div>
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/2.png')" alt="2" class="comentario">
            </div>
        </div>
        <div class="row">
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/3.png')" alt="3" class="comentario">
            </div>
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/4.png')" alt="4" class="comentario">
            </div>
        </div>
        <div class="row pb-5">
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/5.png')" alt="5" class="comentario">
            </div>
            <div class="col-12 col-lg-6 justify-content-center d-flex">
                <img v-bind:src="require('../assets/6.png')" alt="6" class="comentario">
            </div>
        </div>
    </div>
</template>
<style scoped>
    .container-fluid{
        background-color: blue;
    }
    h1{
        color: white;
    }
    img{
        width: 90%;
        height: auto;
    }
    @media (max-width: 576px){
        img.comentario{
            width: 50%;
            height: auto;
        }
    }
</style>