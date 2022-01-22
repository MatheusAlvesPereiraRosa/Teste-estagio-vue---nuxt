<template>
  <div>
    <b-breadcrumb>
      <b-breadcrumb-item href="/">Home</b-breadcrumb-item>
      <b-breadcrumb-item href="/play/firstChallenge"
        >Desafio 1</b-breadcrumb-item
      >
      <b-breadcrumb-item active>Resultado 3</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Você morreu <img class="icon" src="~/assets/touro.png" alt=""></h1>

      <p>
        Os búfalos podem até ter acreditado, mas isso não os impediu de passar
        por cima de você. Morreu atropelado.
      </p>

      <div class="opcoes">
        <NuxtLink to="/"> <button class="sair">Sair</button></NuxtLink>
      </div>
    </div>
  </div>
</template>