<template>
  <header>
    <div class="flex justify-between bg-slate-500 pr-10 pl-10">
      <div class="col-md-12">
        <a href="" class="logo">
          <img src="@/assets/img/logo.svg" alt="DevSolutions Logo" class="py-1">
        </a>
      </div>
      <nav class="flex items-center">
        <ul class="flex">
          <li class="px-2 flex">
            <img class="h-5 px-1" src="@/assets/icons/home.svg"/>
            <a  class="">Home</a>
          </li>
          <li class="px-2 flex">
            <img class="h-5 px-1" src="@/assets/icons/products.svg"/>
            <a  class="">Serviçoes</a>
          </li>
          <li class="px-2 flex">
            <img class="h-5 px-1" src="@/assets/icons/aboutUs.svg"/>
            <a  class="">Sobre nós</a>
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
