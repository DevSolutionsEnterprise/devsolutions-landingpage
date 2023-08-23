<template>
  <swiper-component
    :space-between="30"
    :loop="true"
    :autoplay="{
      delay: 3500,
      disableOnInteraction: false,
    }"
    :pagination="{
      clickable: true,
      dynamicBullets: true,
    }"
    :modules="modules"
    class="mySwiper"
  >
    <swiper-slide>
      <div class="max-w-full max-h-full p-5 transition-all mb-6 md:p-7">
        <h2
          class="text-center mb-6 text-white text-md font-medium max-w-xl transition-all md:text-lg md:text-left lg:text-2xl"
        >
          Desenvolvimento WEB
        </h2>

        <div
          class="container flex flex-col justify-between items-center gap-7 md:flex-row transition-all md:items-start"
        >
          <img
            src="@/assets/imgs/slide/web.png"
            alt="Desenvolvimento web"
            class="max-w-xs transition-all"
          />

          <div class="flex flex-col items-center gap-6 max-w-full">
            <p
              class="text-base text-black font-medium text-justify transition-all md:max-w-sm"
            >
              O serviço de desenvolvimento WEB envolve a criação de sites,
              aplicativos e sistemas que funcionam na internet. O objetivo é
              materializar a ideia do cliente através de uma interface
              interativa e responsiva, que possa ser acessada por qualquer
              dispositivo conectado à rede.
            </p>

            <button
              class="flex justify-center items-center w-44 p-2 bg-secondColor rounded text-white font-description font-semibold leading-normal shadow hover:brightness-105 transition-all md:w-64"
            >
              Tenho uma idéia
            </button>
          </div>
        </div>
      </div>
    </swiper-slide>

    <swiper-slide>
      <div class="max-w-full max-h-full p-5 transition-all md:p-7">
        <h2
          class="text-center mb-6 text-white text-md font-medium max-w-xl transition-all md:text-lg md:text-left lg:text-2xl"
        >
          Desenvolvimento Mobile
        </h2>

        <div
          class="container flex flex-col justify-between items-center gap-7 md:flex-row transition-all md:items-start"
        >
          <img
            src="@/assets/imgs/slide/web.png"
            alt="Desenvolvimento web"
            class="max-w-xs transition-all"
          />

          <div class="flex flex-col items-center gap-6 max-w-full">
            <p
              class="text-base text-black font-medium text-justify transition-all md:max-w-sm"
            >
              O serviço de desenvolvimento mobile envolve a criação de
              aplicativos que funcionam em dispositivos móveis, como smartphones
              e tablets. Hoje a maior parte de nossas tarefas envolvem algum
              aplicativo de celular, ja imaginou o alcance que o seu negócio
              teria ao disponibilizar um aplicativo aos seus clientes?
            </p>

            <button
              class="flex justify-center items-center w-44 p-2 bg-secondColor rounded text-white font-description font-semibold leading-normal shadow hover:brightness-105 transition-all md:w-64"
            >
              Tenho uma idéia
            </button>
          </div>
        </div>
      </div>
    </swiper-slide>

    <swiper-slide>
      <div class="max-w-full max-h-full p-5 transition-all md:p-7">
        <h2
          class="text-center mb-6 text-white text-md font-medium max-w-xl transition-all md:text-lg md:text-left lg:text-2xl"
        >
          WebDesign
        </h2>

        <div
          class="container flex flex-col justify-between items-center gap-7 md:flex-row transition-all md:items-start"
        >
          <img
            src="@/assets/imgs/slide/web.png"
            alt="Desenvolvimento web"
            class="max-w-xs transition-all"
          />

          <div class="flex flex-col items-center gap-6 max-w-full">
            <p
              class="text-base text-black font-medium text-justify transition-all md:max-w-sm"
            >
              O serviço de web design envolve a criação e o planejamento visual
              de sites, aplicativos e sistemas para a web. Isso inclui a escolha
              de cores, tipografia, layout, imagens e elementos gráficos que
              compõem a interface do usuário. O objetivo é criar uma experiência
              de navegação atraente e intuitiva, que reflita a identidade e os
              objetivos da marca ou do produto.
            </p>

            <button
              class="flex justify-center items-center w-44 p-2 bg-secondColor rounded text-white font-description font-semibold leading-normal shadow hover:brightness-105 transition-all md:w-64"
            >
              Tenho uma idéia
            </button>
          </div>
        </div>
      </div>
    </swiper-slide>
  </swiper-component>
</template>

<script setup lang="ts">
import { ref } from 'vue'
import { Swiper as SwiperComponent, SwiperSlide } from 'swiper/vue'
import { Pagination, Autoplay } from 'swiper'

import 'swiper/css'

import 'swiper/css/pagination'

import 'swiper/swiper-bundle.css'

const modules = ref([Pagination, Autoplay])
</script>

<style scoped>
.swiper {
  width: 100%;
  height: 100%;
}

.swiper-slide {
  width: 100% !important;
  text-align: center;
  font-size: 18px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>
