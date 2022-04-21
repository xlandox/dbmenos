<template>
    <div class="container my-5">
        <div class="text-center mb-5">
        <h1>La prensa opina</h1>
    </div>
    <div class="row">
        <div class="col-12 col-lg-4 justify-content-center d-flex">
            <img v-bind:src="require('../assets/Forbes.png')" alt="forbes" class="forbes">
        </div>
        <div class="col-12 col-lg-4 justify-content-center d-flex">
            <img v-bind:src="require('../assets/El-Heraldo.png')" alt="heraldo" class="heraldo">
        </div>
        <div class="col-12 col-lg-4 justify-content-center d-flex">
            <img v-bind:src="require('../assets/Nacional Financiera.png')" alt="nf" class="nf">
        </div>
    </div>
    <div class="row">
        <div class="col-12 justify-content-center d-flex">
            <img v-bind:src="require('../assets/ElEconomista.png')" alt="ee" class="ee">
        </div>
    </div>
    </div>
</template>
<style scoped>
    img{
        width: 70%;
        height: auto;
    }
    h1{
        color: blue;
    }
</style>