<template>
  <div class="flex-col bg bg-dark-blue h-section w-full p-8">
    <h3 class=" font-semibold text-3xl mb-5 text-white ">Não perca a chance de aproveitar esta oportunidade incrível!</h3>
    <div class="flex w-full h-full pt-8">
      <img class=" self-end h-80" src="@/assets/img/rocket.svg" alt="rocket">
      <p class=" font-normal text-2xl w-64 text-white">Registre-se e garanta uma avaliação gratuita da presença online de sua empresa.</p>
      <form class=" bg-white p-7 w-96 ml-auto mr-24 mb-4 rounded-xl h-80">
        <ul>
          <li class="flex justify-between mb-3">
            <label for="" class=" self-center">Nome</label>
            <input type="text" name="Nome" id="" class=" ">
          </li>
          <li class="flex justify-between mb-3">
            <label for="" class=" self-center">Email</label>
            <input type="text" name="Email" id="">
          </li>
          <li class="flex justify-between mb-3">
            <label for="" class=" self-center">Nome da Empresa</label>
            <input type="text" name="Empresa" id="">
          </li>
          <li class="flex">
            <input type="checkbox" name="Empresa" id="" class=" mr-2">
            <label for="">Privacidade e Políticas de Uso</label>
          </li>
          <button class=" bg-light-blue px-3 rounded text-white w-full mt-8">Registrar</button>
        </ul>
      </form>
    </div>
  </div>
</template>

<style scoped>
input {
  background: none;
  font-size: 18px;
  padding: 10px 10px 10px 5px;
  display: block;
  border: none;
  border-radius: 0;
  border-bottom: 1px solid black;
}
input:focus {
  outline: none;
}
</style>
