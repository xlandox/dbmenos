<template>
    <div>
        <nav class="navbar navbar-light bg-primary">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <img src="../assets/logo-header.png" alt="logo" class="logo">
                </a>
                <div class="d-flex collap">
                    <a class="nav-link" href="#">Blog</a>
                    <button type="button" class="btn btn-info">Iniciar Sesion</button>
                </div>
            </div>
        </nav>
    </div>
</template>
<style scoped>
    @media (max-width: 576px){
        img.logo{
            width: 40%;
            height: auto;
        }
        div.collap{
            display: none !important;    
        }
    }
    @media (min-width: 992px){
        img.logo{
            width: 40%;
            height: auto;
        }
        a,button{
            color: white;
            font-weight: 500;
            font-size: 20px;
        }
    }
</style>