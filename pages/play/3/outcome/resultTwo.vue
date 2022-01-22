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
      <b-breadcrumb-item active>Resultado 2</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Você morreu <img class="icon" src="~/assets/alvo.png" alt=""></h1>

      <p>
        Você amarra o homem e se dirige ao laboratório. Você entra
        silenciosamente e consegue chegar ao salão principal, onde você observa
        aproximadamente umas 10 pessoas. Um passo em falso entrega a sua posição
        e você é alvejado. Você morreu.
      </p>

      <div class="opcoes">
        <NuxtLink to="/"> <button class="sair">Sair</button></NuxtLink>
      </div>
    </div>
  </div>
</template>