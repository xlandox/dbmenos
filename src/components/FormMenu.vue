<template>
    <div class="container-fluid fondo-color">
        <div class="cont-form">
            <div class="hombre-form">
                <img v-bind:src="require('../assets/Hombre 2.png')" alt="hombre" class="hombre">
            </div>
            <div class="frase-form">
                <p class="gris">Liquida tus<span class="salto peq"></span> deudas con hasta</p>
                <p class="azul">70% de<span class="salto peq"> descuento</span></p>
            </div>
            <div class="cuerpo-form">
                <div class="cuerpo">
                    <div class="frase-cuerpo text-center">
                        <p>Somos la solucion a<span class="salto"></span> tus deudas</p>
                    </div>
                    <div class="form">
                        <div class="input-nombre mb-3 d-flex justify-content-center">
                            <input type="text" class="nombre-completo" placeholder="Nombre completo">
                        </div>
                        <div class="input-tel mb-3 d-flex justify-content-center">
                            <input type="tel" class="tel" placeholder="Numero">
                        </div>
                        <div class="boton d-flex justify-content-center">
                            <input class="btn btn-warning" type="submit" value="INICIAR">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
    @media (max-width: 576px){
        .fondo-color{
            padding-top: 10px;
            padding-left: 0;
            padding-right: 0;
        }
        .cont-form{
            display: grid;
            grid-template-columns: 50% 50%;
            gap: 10px;
        }
        .hombre{
            width: 60%;
            height: auto;
        }
        .hombre-form{
            display: flex;
            justify-content:end
        }
        .gris{
            color: gray;
            font-size: 10px;
            line-height: 1.6;
            word-spacing: 0.25em;
            letter-spacing: 0.10em;
        }
        .azul{
            color: blue;
            font-size: 15px;
            font-weight: 700;
            line-height: 1.6;
            word-spacing: 0.25em;
            letter-spacing: 0.10em;
        }
        .cuerpo-form{
            grid-row: 2/3;
            grid-column: 1/3;
            background-image: url("../assets/Fondo azul escritorio.png");
            background-position: center;
            background-repeat: no-repeat;
        }
        div.frase-cuerpo p{
            color: white;
            font-size: 15px;
            font-weight: 700;
            margin: 10px 0;
        }
        input.nombre-completo,
        input.tel{
            width: 65%;
            height: 30px;
        }
        input.btn-warning{
            color: blue;
            font-weight: 700;
        }
        .boton{
            padding-bottom: 10px;
        }
        .peq{
            display: block;
        }
    }
    @media (min-width: 992px){
        .fondo-color{
            background-color: beige;
            padding-top: 60px;
        }
        .cont-form{
            display: grid;
            grid-template-columns: 33% 33% 33%;
        }
        img.hombre{
            width: 90%;
            height: auto;
        }
        .gris{
            color: gray;
            font-size: 23px;
            line-height: 1.6;
            word-spacing: 0.25em;
            letter-spacing: 0.10em;
        }
        .azul{
            color: blue;
            font-size: 35px;
            font-weight: 700;
            line-height: 1.6;
            word-spacing: 0.25em;
            letter-spacing: 0.10em;
        }
        .salto{
            display: block;
        }
        .cuerpo{
            width: 100%;
            height: 85%;
            background-image: url("../assets/Fondo azul escritorio.png");
            background-position: center;
            background-repeat: no-repeat;
        }
        div.frase-cuerpo p{
            color: white;
            font-size: 30px;
            font-weight: 700;
            padding: 50px 0;
        }
        .form{
            justify-content: center;
        }
        input.nombre-completo,
        input.tel{
            width: 85%;
            height: 50px;
        }
        input.btn-warning{
            color: blue;
            font-weight: 700;
            width: 45%;
        }
    }
</style>


