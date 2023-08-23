<script setup lang="ts">
import SlideServices from '@/components/SlideServices/index.vue'
</script>

<template>
  <section class="flex pt-10 pb-6 px-4 transition-all lg:pb-8 xl:pb-2">
    <div
      class="container m-auto w-full flex justify-center items-center flex-col"
    >
      <h1
        class="max-w-5xl text-black text-lg font-title font-medium leading-normal text-center transition-all sm:text-xl md:text-2xl lg:text-3xl"
      >
        Descubra como podemos transformar sua visão em realidade.
      </h1>

      <h2
        class="max-w-5xl text-black text-xl font-title font-bold leading-normal text-center transition-all sm:text-2xl md:text-3xl lg:text-4xl"
      >
        Explore nossos serviços agora!
      </h2>

      <div
        class="container flex flex-col justify-center items-center gap-4 bg-primaryColor p-4 mt-12 rounded-2xl transition-all md:p-8 lg:flex-row lg:justify-between lg:items-start lg:p-10"
      >
        <div>
          <h2
            class="mt-6 text-center text-white text-4xl transition-all lg:text-left lg:max-w-xs"
          >
            Os principais serviços de tecnologia do mercado!
          </h2>

          <p
            class="mt-6 text-center text-white text-xl transition-all lg:text-left lg:max-w-xs lg:text-lg"
          >
            Nossa equipe é capacitada em desenvolver as principais ferramentas
            que as maiores empresas utilizam.
          </p>
        </div>

        <div class="box-slide">
          <SlideServices />
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="postcss">
.font-title {
  font-family: 'Montserrat', sans-serif;
}

.box-slide {
  @apply relative container m-auto flex justify-center items-center gap-4 rounded-2xl z-10 transition-all;
  background-color: #6ab5d7;

  @media (min-width: 1024px) {
    max-width: 660px;
    max-height: 26rem;
  }

  @media (min-width: 1280px) {
    min-width: 800px;
  }
}
</style>
