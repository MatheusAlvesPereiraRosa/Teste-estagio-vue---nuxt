<template>
  <div>
    <b-breadcrumb>
      <b-breadcrumb-item href="/">Home</b-breadcrumb-item>
      <b-breadcrumb-item active>Desafio 1</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Desafio 1</h1>

      <p>
        Você acordou na floresta tonto e com uma grande dor de cabeça, sem
        nenhuma memória de como foi parar ali. Um barulho cada vez mais intenso
        foi o que despertou você desse apagão. Após abrir os olhos e
        levantar-se, você observa uma manada de búfalos vindo em sua direção, a
        pouquíssimos metros de distância. O que você faz?
      </p>

      <div class="opcoes">
        <NuxtLink to="/play/1/outcome/resultOne">
          <button class="opcao">Corre o mais rápido possível</button>
        </NuxtLink>

        <NuxtLink to="/play/1/outcome/resultTwo">
          <button class="opcao">Sobe na árvore</button>
        </NuxtLink>

        <NuxtLink to="/play/1/outcome/resultTree">
          <button class="opcao">Se finge de morto</button>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>