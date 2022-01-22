<template>
  <div>
    <b-breadcrumb>
      <b-breadcrumb-item href="/">Home</b-breadcrumb-item>
      <b-breadcrumb-item href="/play/firstChallenge"
        >Desafio 1</b-breadcrumb-item
      >
      <b-breadcrumb-item active>Resultado 2</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Você conseguiu</h1>

      <p>Você sobe na árvore e escapa por pouco da manada</p>

      <div class="opcoes">
        <NuxtLink to="/play/secondChallenge">
          <button class="avancar">Próxima etapa</button></NuxtLink
        >
      </div>
    </div>
  </div>
</template>