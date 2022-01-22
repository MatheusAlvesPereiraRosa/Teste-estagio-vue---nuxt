<template>
  <div>
    <b-breadcrumb>
      <b-breadcrumb-item href="/">Home</b-breadcrumb-item>
      <b-breadcrumb-item href="/play/firstChallenge"
        >Desafio 1</b-breadcrumb-item
      >
      <b-breadcrumb-item active>Desafio 2</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Desafio 2</h1>

      <p>
        Ao ver que a manada passou, você desce da árvore e começa a explorar a
        região em busca de respostas. Não muito distante dali, você encontra um
        acampamento abandonado e um bilhete com instruções, deixado para trás.
        Antes que você possa alcançar o bilhete, um homem aparece com uma
        marreta gritando e avançando em sua direção. No seu corpo a adrenalina
        dispara. O que você faz?
      </p>

      <div class="opcoes">
        <NuxtLink to="/play/2/outcome/resultOne">
          <button class="opcao">Foge para bem longe</button>
        </NuxtLink>

        <NuxtLink to="/play/2/outcome/resultTwo">
          <button class="opcao">Pega o bilhete e foge para bem longe</button>
        </NuxtLink>

        <NuxtLink to="/play/2/outcome/resultTree">
          <button class="opcao">
            Puxa toda coragem do coração e enfrenta o homem
          </button>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>