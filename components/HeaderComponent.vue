<template>
  <header class=" h-16 fixed top-0 w-full z-10">
    <div class="flex justify-between bg-slate-500 pr-10 pl-10 h-full">
        <a href="" class="flex justify-center items-center">
          <img src="@/assets/imgs/logo.png" alt="DevSolutions Logo" class=" h-full py-3">
        </a>
      <nav class="flex items-center">
        <ul class="flex">
          <li class="px-2 flex">
            <img class="h-5 px-1" src="@/assets/icons/home.svg"/>
            <a  class=" text-white" href="#homeSection">Home</a>
          </li>
          <li class="px-2 flex ">
            <img class="h-5 px-1 fill-white" src="@/assets/icons/products.svg"/>
            <a  class="text-white" href="#serviceSection">Serviçoes</a>
          </li>
          <li class="px-2 flex">
            <img class="h-5 px-1" src="@/assets/icons/aboutUs.svg"/>
            <a  class="text-white" href="#aboutUsSection">Sobre nós</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script setup lang="ts">
const menuItens = reactive([
  {
    label: 'Home',
    url:'/',
    src: 'home.svg'
  },
  {
    label: 'Serviços',
    url:'/services',
    src: 'products.svg'
  },
  {
    label: 'Sobre Nós',
    url:'/aboutUs',
    src: 'aboutUs.svg'
  },
])

</script>

<style scoped>


</style>
