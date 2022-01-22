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
      <b-breadcrumb-item active>Resultado 1</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Você morreu <img class="icon" src="~/assets/caveira.png" alt=""></h1>

      <p>
        Você consegue fugir do local e voltar à cidade, porém sem nenhuma ideia
        de quem o atacou. Você continua tentando juntar as peças do
        quebra-cabeças. 2 semanas depois você morre atropelado,
        “acidentalmente”, ao sair de casa.
      </p>

      <div class="opcoes">
        <NuxtLink to="/"> <button class="sair">Sair</button></NuxtLink>
      </div>
    </div>
  </div>
</template>