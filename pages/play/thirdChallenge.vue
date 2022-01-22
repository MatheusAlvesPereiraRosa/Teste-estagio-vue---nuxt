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
      <b-breadcrumb-item active>Desafio 3</b-breadcrumb-item>
    </b-breadcrumb>

    <div class="container-jogo">
      <h1>Desafio 3</h1>

      <p>
        Você finalmente consegue ler o bilhete: “Vamos fazer parecer um
        acidente. Misture o conteúdo deste frasco na comida dele. O remédio vai
        começar a fazer efeito depois de 30 minutos. Quando ele estiver
        completamente apagado, leve-o até o pé da árvore mais alta no início da
        floresta e direcione a manada de búfalos em sua direção. Estaremos
        esperando no laboratório ao norte do acampamento.” O que você faz?
      </p>

      <div class="opcoes">
        <NuxtLink to="/play/3/outcome/resultOne"
          ><button class="opcao">Foge e liga para a polícia</button>
        </NuxtLink>

        <NuxtLink to="/play/3/outcome/resultTwo"
          ><button class="opcao">Amarra o homem e vai ao laboratório</button>
        </NuxtLink>

        <NuxtLink to="/play/3/outcome/resultTree"
          ><button class="opcao">
            Mata o homem, pega a marreta e vai ao laboratório
          </button>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>