<template>
    <div class="container pt-5">
        <div class="row">
            <div class="cont-quienes justify-content-center">
                <div>
                    <img v-bind:src="require('../assets/Ilustracion pregunta-2.png')" alt="pregunta" class="pregunta">
                </div>
                <div>
                    <h1 class="quienes">Quienes Somos ?</h1>
                </div>
            </div>
        </div>
        <div class="text-left">
            <p class="descri">DB Menos es una plataforma digital enfocada en liquidar deudas atrasadas con trajetas de credito, departamentales o prestamos personales.</p>
        </div>
    </div>
</template>
<style scoped>
    h1.quienes{
        color: blue;
    }
    @media (max-width: 576px){
        .cont-quienes{
            display: flex;
            align-items: center;
        }
        .pregunta{
            width: 70px;
            height: auto;
            margin-right: 40px;        
        }
        p.descri{
            font-size: 20px;
            font-weight: 400;
        }
    }
    @media (min-width: 992px){
        .cont-quienes{
            display: flex;
            align-items: center;
        }
        .pregunta{
            margin-right: 50px;        
        }
        p.descri{
            font-size: 40px;
            font-weight: 400;
        }
    }
</style>