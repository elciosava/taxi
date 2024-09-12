<script setup> 
</script>

<template>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&display=swap" rel="stylesheet">
    <div id="container">
        <div id="nav">
            <div class="left">
                <nav>
                    <ul>
                        <li>Inicio</li>
                        <li>Turismo</li>
                        <li>Sobre</li>
                    </ul>
                </nav>
            </div>
            <div id="logo">
                <div class="logo_meio">
                    <img src="../assets/img/logo.svg" alt="">
                </div>
            </div>
            <div class="right">
                <nav>
                    <ul>
                        <li>Galeria</li>
                        <li>História</li>
                        <li>Contato</li>
                    </ul>
                </nav>
            </div>
        </div>
    </div>
</template>

<style scoped>

    #container{
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        justify-content: center;
        align-items: center;
        position: fixed;
        background-color: #ffffff;
    }
    #nav{
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        justify-content: space-evenly;
        align-items: center;
        width: 1500px;
        height: 150px;
        font-family: "Roboto Mono", monospace;
        font-optical-sizing: auto;
        font-weight: bold;
        font-style: normal;
        font-size: 20px;

        ul li{
            list-style: none;
            display: inline-block;
            margin-left: 20px;
            margin-right: 20px;
        }

    }
</style>
