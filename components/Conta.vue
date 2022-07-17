<template>
  <div class="container conteudo">
    <div class="d-flex justify-content-start flex-column p-0">
      <img src="https://static.xx.fbcdn.net/rsrc.php/y8/r/dF5SId3UHWd.svg" alt="" width="200px" class="logo">
      <h3>Logins recentes</h3>
      <p>Clique na sua foto ou adicione uma conta.</p>
    </div>
    <div class="d-flex p-0">
      <b-card
        title="Nome de usuário"
        img-src="~/assets/foto-usuario.jpg"
        img-alt="Imagem do usuário"
        img-top
        tag="article"
        style="width: 160px; height: 160px;"
        class="mb-2 text-center mr-3 hover"
      >
      </b-card>
      <b-card
        title="Adicionar conta"
        img-src="~/assets/botao-mais.webp"
        img-alt="Clique para adicionar um usuário"
        img-top
        tag="article"
        style="width: 160px; height: 160px;"
        class="mb-2 text-center plus"
      >
      </b-card>
    </div>
  </div>
</template>

<style scoped>
  div{
    padding-top: 92px;
    padding-bottom: 132px;
    background-color: #f0f2f5;
    font-family: SFProDisplay, Helvetica, Arial, sans-serif;
  }
  .logo{
    margin: -20px;
    padding: 8px 0 16px 0;
  }
  h3{
    font-size: clamp(1.7em, 2em + 1vw, 1.5em);
  }
  p{
    padding-bottom: 12px;
    color: #606770;
    font-size: clamp(0.2em, 0.2em + 1vw, 1.5em);
  }
  .card-title{
    background-color: white;
    color: #4b4f56;
    font-size: clamp(0.2em, 0.2em + 1vw, 1.5em);
    margin-bottom: 0;
    padding: 12px;
    border-bottom-left-radius: 8px;
    border-bottom-right-radius: 8px;
  }
  .card-img-top, .card{
    border-top-right-radius: 8px;
    border-top-left-radius: 8px;
  }
  .card-body{
    padding: 0;
    margin: 0;
  }
  .card:hover{
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
  }
</style>
