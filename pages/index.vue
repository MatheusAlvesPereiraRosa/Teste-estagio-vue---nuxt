<template>
  <div>
    <b-breadcrumb>
      <b-breadcrumb-item active>Home</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Seja bem vindo ao nosso jogo</h1>

      <p>Esse joguinho foi feito com o objetivo de passar em um teste de estágio para uma vaga de nuxt e vue. É um jogo de decisões
        em que sua decisão pode te levar ao seu próximo desafio ou te matar, então escolha bem e tente passar pelos três desafios. Espero que goste de jogar ; )</p>
      <div class="opcoes">
        <NuxtLink to="/play/firstChallenge">
          <button class="avancar">Começar</button>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
