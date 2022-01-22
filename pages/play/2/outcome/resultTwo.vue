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
      <b-breadcrumb-item active>Resultado 2</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Você morreu <img class="icon" src="~/assets/caveira.png" alt=""></h1>

      <p>
        O homem lhe alcançou enquanto você tentava pegar o bilhete e lhe acertou
        uma marretada. Você morreu
      </p>

      <div class="opcoes">
        <NuxtLink to="/"> <button class="sair">Sair</button></NuxtLink>
      </div>
    </div>
  </div>
</template>