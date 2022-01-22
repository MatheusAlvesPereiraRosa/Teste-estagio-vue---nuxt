<template>
  <div>
    <b-breadcrumb>
      <b-breadcrumb-item href="/">Home</b-breadcrumb-item>
      <b-breadcrumb-item href="/play/firstChallenge"
        >Desafio 1</b-breadcrumb-item
      >
      <b-breadcrumb-item active>Resultado 1</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Você morreu <img class="icon" src="~/assets/touro.png" alt=""></h1>

      <p>
        A sua corrida não foi suficiente para superar a da manada. Você morreu
        atropelado.
      </p>

      <div class="opcoes">
        <NuxtLink to="/"> <button class="sair">Sair</button></NuxtLink>
      </div>
    </div>
  </div>
</template>

