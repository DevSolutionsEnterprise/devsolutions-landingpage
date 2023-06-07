<template>
  <section class="flex pt-10 pb-6 px-4 lg:pb-8 xl:pb-2">
    <div class="w-full">
      <h1
        class="max-w-4xl m-auto mb-12 text-thirdColor text-2xl font-title font-bold leading-normal text-center transition-all sm:text-3xl lg:text-4xl"
      >
        Por que investir em uma presença online é essencial para o sucesso do
        meu negócio?
      </h1>

      <div
        class="container flex flex-col justify-center items-center gap-4 m-auto transition-all lg:flex-row-reverse lg:items-start"
      >
        <div
          class="flex flex-col justify-center items-center ml-6 transition-all"
        >
          <p class="text text-black">
            <span class="text-thirdColor font-bold">
              Ter presença online é crucial para qualquer negócio hoje em dia.
            </span>
            Ajuda a aumentar visibilidade do seu produto, a quantidade de
            clientes e reputação da marca, ocasionando bons relacionamentos e
            mais vendas!
          </p>

          <q class="text mt-8 text-thirdColor font-bold">
            Não estar presente online significa perder oportunidades de crescer
            e expandir.
          </q>

          <p class="text text-black mt-12">
            <strong>Clique abaixo</strong> para receber uma avaliação gratuita
            de como tornar a experiência online de sua empresa marcante para
            seus clientes.
          </p>

          <button
            class="flex justify-center items-center w-64 p-2 mt-6 bg-secondColor rounded text-white font-description font-semibold leading-normal shadow hover:brightness-105 transition-all"
          >
            Receber Avaliação
          </button>
        </div>

        <img
          src="@/assets/imgs/avaliable.png"
          alt="computardor"
          class="max-w-xs transition-all md:max-w-sm lg:relative xl:-top-24 xl:-right-20 xl:max-w-xl"
        />
      </div>
    </div>
  </section>
</template>

<style scoped lang="postcss">
.font-title {
  font-family: 'Saira Semi Condensed', sans-serif;
}
.font-description {
  font-family: 'Montserrat', sans-serif;
}

.text {
  @apply max-w-3xl text-center text-base font-description leading-normal lg:text-xl;
}
</style>
