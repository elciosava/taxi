<script setup>

</script>

<template>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&display=swap" rel="stylesheet">
        <section id="cidade">
            <div class="cidades">
                <div class="bomjardim">
                    <h1>BOM JARDIN DA SERRA</h1>
                </div>
                <div class="urubici">
                    <h1>URUBICI</h1>
                </div>
                <div class="saojoaquim">
                    <h1>SÃO JOAQUIM</h1>
                </div>
            </div>
        </section>
</template>

<style>
    body{
        font-family: "Roboto Mono", monospace;
        font-optical-sizing: auto;
        font-weight: bold;
        font-style: normal;
    }
    #container{
        display: flex;
        flex-direction: row;
        align-content: center;
        align-items: center;
        justify-content: space-evenly;
        flex-wrap: nowrap;
        font-weight: bold;
        width: 1500px;
        }
        .cidades{
            display: flex;
            padding: 20px;
            align-items: center;
            justify-content: space-around;
            flex-wrap: nowrap;
            flex-direction: row;
            font-size: 30px;
        }
</style>
