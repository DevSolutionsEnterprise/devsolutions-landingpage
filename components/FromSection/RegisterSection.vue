<template>
  <section class="flex pt-10 px-4 mt-6 lg:pb-8 xl:pb-2 bg-primaryColor">
    <div class="flex w-full">
      <div class=" mr-8">
        <h3 class=" max-w-2xl text-white text-xl font-title font-bold leading-normal transition-all sm:text-2xl lg:text-4xl xl:text-5xl">Não perca a chance de aproveitar esta oportunidade incrível!</h3>
        <div class="flex mt-8">
          <img class="  h-96" src="@/assets/imgs/rocket.svg" alt="rocket">
          <p class=" font-normal text-2xl  text-white text-right">Registre-se e garanta uma avaliação gratuita da presença online de sua empresa.</p> 
        </div>
      </div>
      <div class="form">
        <form class=" bg-white p-7 w-96 rounded-xl  max-w-sm">
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
            <li class="flex mb-3">
              <input type="checkbox" name="Empresa" id="" class=" mr-2">
              <label for="">Privacidade e Políticas de Uso</label>
            </li>
            <button
              class="flex justify-center items-center w-full p-2 mt-6 bg-secondColor rounded text-white font-description font-semibold leading-normal shadow hover:brightness-105 transition-all"
            >
              Registrar
            </button>
          </ul>
        </form>
      </div>
    </div>
  </section>
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

.form {
  width: 50%;
}
</style>
