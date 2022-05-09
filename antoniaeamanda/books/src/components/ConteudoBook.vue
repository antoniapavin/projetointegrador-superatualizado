<template>
  <main id="content" class="conteudo-book">
    <div class="livro-conteudo">
      <div class="imagem-livro">
        <img
          src="@/assets/img/pedra-filosofal.jpg"
          alt=""
        />
      </div>
      <p class="titulo-livro">Harry Potter e a Pedra Filosofal</p>
      <p class="resumo-livro">
        Harry Potter é um garoto órfão que vive infeliz com seus tios, os
        Dursleys. Ele recebe uma carta contendo um convite para ingressar em
        Hogwarts, uma famosa escola especializada em formar jovens bruxos ver
        mais...
      </p>
    </div>
  </main>
</template>

<style>
.conteudo-book {
  background-color: #c4c4c4;
  display: flex;
  justify-content: center;
  align-items: center;
}

.livro-conteudo {
  width: 40%;
  height: 90%;
  border-radius: 13px;
  padding: 0 40px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background: url(@/assets/img/estantefundo.png);

}

.titulo-livro {
  font-family: "IBM Plex Serif", serif;
  font-size: 30px;
}

.resumo-livro {
  font-family: "IBM Plex Serif", serif;
  font-size: 1.2em;
}

img {
  padding-left: 120px;
  padding-right: 120px;
  width: 50%;
}
</style>
