<script setup>

</script>

<template>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&display=swap" rel="stylesheet">
        <section id="home">
            <div id="container">
                <div class="img">
                    <img src="../assets/img/taxi.svg" alt="">
                </div>
                <div class="text">
                    <p class="vermelho">PRECISA DE UMA CORRIDA?</p>
                    <p class="sem_cor">O MELHOR SERVIÇO DE <strong class="amarelo">TAXI</strong> E <br>
                    <strong class="amarelo">TURISMO</strong> DE URUBICI VOCÊ <br>
                    ENCONTRA AQUI!</p>
                    <button>Contrate Agora</button>
                </div>
            </div>
            
        </section>
</template>

<style scoped>
    #container{
        display: flex;
        flex-direction: row;
        align-content: center;
        align-items: center;
        justify-content: space-evenly;
        flex-wrap: nowrap;
        font-weight: bold;
        width: 1500px;
        height: calc(100vh - 150px);

        .img{
            margin-top: 90px;
        }

        .sem_cor{
            text-align: right;
            font-family: "Roboto Mono", monospace;
            font-optical-sizing: auto;
            font-weight: bold;
            font-style: normal;
            font-size: 46px;
        }
        .vermelho{
            color: red;
            text-align: right;
            font-family: "Roboto Mono", monospace;
            font-optical-sizing: auto;
            font-weight: bolder;
            font-style: normal;
            font-size: 46px;
        }
        .amarelo{
            color:#ffc700;
        }
        button{
            background-color: black;
            color: #ffffff;
            width: 440px;
            height: 55px;
            border: none;
            font-size: 30px;
            margin-top: 15px;
        }

        .text {
            align-items: flex-end;
            flex-direction: column;
            display: flex;
            font-size: 50px;            
        }
    }
</style>
