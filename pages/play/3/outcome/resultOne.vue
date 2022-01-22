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
      <b-breadcrumb-item active>Resultado 1</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Você conseguiu</h1>

      <p>
        Você informa a polícia o que aconteceu e passa a localização do
        laboratório. Chegando lá ela se depara com um sítio de produção de
        cocaína e prende todos os presentes. As evidências sugerem que você
        ainda pode estar em perigo, por este motivo a polícia lhe coloca no
        programa de proteção à testemunha e você sobrevive para vivenciar uma
        nova história. Parabéns, você ganhou!
      </p>

      <div class="opcoes">
        <NuxtLink to="/"
          ><button class="avancar">Voltar para a tela inicial</button></NuxtLink
        >
      </div>
    </div>
  </div>
</template>