<template>
  <section class="flex pt-10 pb-6 px-4 bg-primaryColor lg:pb-8 xl:pb-2">
    <div
      class="container m-auto flex flex-col justify-center items-center gap-4 transition-all md:flex-row"
    >
      <div
        class="flex flex-col justify-center items-center transition-all md:items-start"
      >
        <h1
          class="max-w-2xl text-white text-xl font-title font-bold leading-normal text-center transition-all sm:text-2xl md:text-start lg:text-4xl xl:text-5xl"
        >
          Não deixe a oportunidade de melhorar sua presença na WEB escapar!
        </h1>

        <p
          class="mt-6 text-white text-md font-description max-w-xl md:text-lg lg:text-2xl"
        >
          Para descobrir como nossas soluções digitais podem ajudá-lo a alcançar
          o sucesso online de sua empresa
          <strong>CLIQUE NO BOTÃO ABAIXO</strong> para receber uma avaliação
          gratuita!
        </p>

        <button
          class="flex justify-center items-center w-64 p-2 mt-6 bg-secondColor rounded text-white font-description font-semibold leading-normal shadow hover:brightness-105 transition-all"
        >
          Quero receber!
        </button>
      </div>

      <img
        src="@/assets/imgs/first-image.png"
        alt="ferramentas tecnologicas"
        class="max-w-xs transition-all md:mt-12 md:max-w-sm lg: xl:max-w-xl"
      />
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
</style>
