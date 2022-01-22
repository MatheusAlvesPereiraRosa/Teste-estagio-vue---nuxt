<template>
  <div>
    <b-breadcrumb>
      <b-breadcrumb-item href="/">Home</b-breadcrumb-item>
      <b-breadcrumb-item href="/play/firstChallenge"
        >Desafio 1</b-breadcrumb-item
      >
      <b-breadcrumb-item href="/play/secondChallenge"
        >Desafio 2</b-breadcrumb-item
      >
      <b-breadcrumb-item href="/play/thirdChallenge"
        >Desafio 3</b-breadcrumb-item
      >
      <b-breadcrumb-item active>Resultado 3</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Você morreu <img class="icon" src="~/assets/alvo.png" alt=""></h1>

      <p>
        Você mata o homem, pega a marreta e se dirige ao laboratório. Ao avistar
        2 guardas na entrada, confiante de si e seus feitos recentes, você corre
        na direção dos guardas, segurando a marreta com as duas mãos levantadas
        acima da sua cabeça e gritando “LEEROY JEENKINS!!!!”. Infelizmente, o
        efeito surpresa foi prejudicado e os guardas não tiveram dificuldade em
        alvejá-lo. Você morreu.
      </p>

      <div class="opcoes">
        <NuxtLink to="/"> <button class="sair">Sair</button></NuxtLink>
      </div>
    </div>
  </div>
</template>