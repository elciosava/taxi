<script setup>
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';
import 'swiper/css/navigation';

// Import required modules
import { Navigation } from 'swiper/modules';

// Declare the modules to be used
const modules = [Navigation];
</script>

<template>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&display=swap"
        rel="stylesheet">
    <section id="home">
        <div id="container">
            <div class="text">
                <p>NOSSO SERVIÇO DE GUIA TURÍSTICO <br>
                    TE OFERECE A MELHOR EXPERIÊNCIA <br>
                    EM URUBICI E REGIÃO, COM <br>
                    PROFISSIONAIS PREPARADOS E QUE <br>
                    CONHECEM OS MELHORES PONTOS <br>
                    TURÍSTICOS!</p>
                    <button>SABER MAIS</button>
            </div>
            <div class="carrocel">
                <swiper :navigation="true" :modules="modules" class="mySwiper">
                    <swiper-slide><img src="../assets/img/slide1.png" alt=""></swiper-slide>
                    <swiper-slide><img src="../assets/img/slide2.png" alt=""></swiper-slide>
                    <swiper-slide><img src="../assets/img/slide3.png" alt=""></swiper-slide>
                    <swiper-slide><img src="../assets/img/slide4.png" alt=""></swiper-slide>
                    <swiper-slide><img src="../assets/img/slide5.png" alt=""></swiper-slide>
                </swiper>
            </div>
        </div>
        <div id="miniaturas">
            <p>nhjhjghhjg</p>
        </div>

    </section>
</template>

<style scoped>
.swiper {
    width: 700px;
    height: 400px;
}

#container {
    display: flex;
    flex-direction: row;
    align-content: center;
    align-items: center;
    justify-content: space-evenly;
    flex-wrap: nowrap;
    font-weight: bold;
    width: 1500px;
    height: calc(100vh - 150px);

    .text {
        font-family: "Roboto Mono", monospace;
        font-optical-sizing: auto;
        font-weight: bold;
        font-style: normal;
        font-size: 35px;
    }

    p {
        text-align: justify;
    }
    button{
            background-color: #007119;
            color: #fff;
            width: 440px;
            height: 55px;
            border: none;
            font-size: 30px;
            margin-top: 40px;
        }

    .carrocel {
        width: 700px;
        height: 400px;
        box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.5);
    }
}
</style>
