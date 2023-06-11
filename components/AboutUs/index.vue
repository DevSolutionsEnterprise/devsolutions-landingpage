<template>
  <section class="flex pt-10 pb-6 px-4 mt-6 lg:pb-8 xl:pb-2">
    <div class="container m-auto relative">
      <div class="flex flex-col justify-center items-center transition-all">
        <h1
          class="text-black text-2xl font-title font-medium leading-normal text-center transition-all sm:text-3xl lg:text-4xl"
        >
          Quem somos nós?
        </h1>

        <p
          class="mt-6 text-center text-black text-md font-description leading-normal lg:text-xl"
        >
          Somos uma equipe de desenvolvedores de software com anos de
          experiência profissional. Combinamos nossas forças de vontade e
          inteligência contextual para criar soluções de software eficientes e
          eficazes. Com a vasta experiência em ferramentas tecnológicas somos
          capazes de enfrentar os desafios mais complexos e variados
          possíveis!<br /><br />
          A abordagem colaborativa é uma peça chave de nosso produto. Nossa
          equipe trabalha em estreita colaboração com o cliente para desenvolver
          a solução ideal para ele, atendendo perfeitamente suas necessidades.
          Nossa obstinação garante que cada linha de código seja escrita com a
          máxima atenção aos detalhes, para que a solução final seja robusta,
          escalável e fácil de manter.
        </p>

        <div
          class="flex flex-col justify-center items-center w-full gap-4 mt-6 transition-all md:flex-row md:items-start md:gap-18 lg:gap-32"
        >
          <div>
            <h1 class="title">Valores</h1>

            <ul class="flex flex-col items-center gap-3">
              <li class="text font-description">Igualdade;</li>
              <li class="text font-description">Respeito;</li>
              <li class="text font-description">Confiança;</li>
              <li class="text font-description">Compromisso;</li>
              <li class="text font-description">Satisfação do Cliente;</li>
            </ul>
          </div>

          <div>
            <h1 class="title">Visão</h1>

            <p class="text font-description">
              Proporcionar soluções tecnológicas inovadoras que transformam
              positivamente a vida das pessoas e empresas.
            </p>
          </div>

          <div>
            <h1 class="title">Missão</h1>

            <p class="text font-description">
              Nosso objetivo é desenvolver um empreendimento consistente e
              duradouro, que se destaque em seus setores de atuação como líder
              em qualidade de produtos, atendimento e serviços, proporcionando
              aos nossos clientes uma experiência única e satisfatória.
            </p>
          </div>
        </div>
      </div>

      <img
        src="@/assets/imgs/about-us.png"
        alt="ferramentas tecnologicas"
        class="absolute top-0 right-1/2 translate-x-2/4 hidden transition-all sm:block md:max-h-full"
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

.title {
  @apply mb-6 text-black text-xl font-title font-bold leading-normal text-center transition-all sm:text-2xl;
}

.text {
  @apply text-center;
  max-width: 240px;
}
</style>
