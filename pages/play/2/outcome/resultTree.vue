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
      <b-breadcrumb-item active>Resultado 3</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Você conseguiu</h1>

      <p>
        Você consegue desviar da primeira marretada do homem, que fica ocioso
        por um curto período, o suficiente para você acertá-lo em cheio na
        cabeça e apagá-lo no chão.
      </p>

      <div class="opcoes">
        <NuxtLink to="/play/thirdChallenge">
          <button class="avancar">Próxima etapa</button></NuxtLink
        >
      </div>
    </div>
  </div>
</template>