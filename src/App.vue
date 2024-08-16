<script setup>

</script>

<template>
  <header>
    <div class="logo">
      <img class="icon" src="../src/img/computador-portatil.png" alt="icon">
      <h1>Sr. Elvis</h1>
    </div>

    <ul class="list">
      <li>Manutenção</li>
      <li>Equipamentos</li>
      <li>Orçamentos</li>
      <li>Entrar</li>
      <li><img class="pessoa" src="../src/img/perfil.png" alt="icone-cadastro"></li>
    </ul>
  </header>

  <section>
    <div class="padding">
      <div class="container">
        <div class="item cabecalho">Oferecemos um atendimento personalizado e orçamentos</div>

        <div class="item menu-lateral">
          <p>No Sr. Elvis, estamos comprometidos em oferecer serviços de alta qualidade para atender todas as suas
            necessidades relacionadas a celulares. Nossa missão é proporcionar soluções rápidas e eficazes, garantindo a
            melhor experiência para você.</p>
        </div>

        <div class="item principal"><img src="../src/img/computador.png" alt="computador"></div>
      </div>
    </div>

  </section>
  <section>
    <div>

      <h4>Disponibilizamos uma vasta gama de peças de reposição e acessórios para celulares.</h4>

      <div class="imagens">
        <div class="contem"><img src="../src/img/capinha_amarela.jpg" alt="capa-amarela-iphone" height="300px"></div>
        <div class="contem"><img src="../src/img/capa_preta_iphone.webp" alt="capas-samsung" height="300px"></div>
      </div>
    </div>
  </section>

  <footer>
    <div>
      <p>Nossos serviços</p>
    </div>
    <div>
      <p>Nossa empresa</p>
    </div>
    <div>
      <p>Quem somos</p>
    </div>
    <div><img class="icones" src="../src/img/instagram (1).png" alt="icone-instagram"></div>
    <div><img class="icones" src="../src/img/twitter (1).png" alt="icone-x"></div>
    <div><img class="icones" src="../src/img/telefone.png" alt="icone-whatsapp"></div>
  </footer>
 
</template>

<style scoped>
header {
  padding: 1rem;
  background-color: #FFFF0D;
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  align-items: center;
}

.list {
  display: grid;
  column-gap: 1rem;
  grid-template-columns: auto auto auto auto auto;
  align-items: center;
}

.logo {
  display: grid;
  grid-template-columns: auto auto;
  align-items: center;
  column-gap: .5rem;
}

.icon {
  width: 50px;
  height: 50px;
}

.pessoa {
  width: 35px;
  height: 35px;
}

/*.padding{
    padding: 10rem;
    background-color: #FFFF48;
    margin-top: 1%;
    display: grid;
    grid-template-areas: "item-1""item-3""item-2";
  }
    */
.padding {
  margin-top: 2%;
  background-color: #FFFF48;
  margin-bottom: 5%;
}

.container {
  padding: 10rem;
  display: grid;
  grid-template: 100px 150px 100px / 1fr 1fr;
  grid-template-areas:
    "cabecalho cabecalho cabecalho"
    "menu-lateral principal principal";

}

.cabecalho {
  grid-area: cabecalho;
  text-align: center;

}

.menu-lateral {
  grid-area: menu-lateral;
}

.principal {
  grid-area: principal;
  text-align: right;
  width: 600px;

}

.imagens {
  display: grid;
  align-items: center;
  grid-template-columns: 45% 55%;

}

.item {
  font-size: 2rem;
}

.contem {
  text-align: center;
  /* margin-top: 3%; */
  /* text-align: center;
  font-size: 1.25em;
  font-weight: normal; */

  & img:hover {
    margin: -30px;
    height: 330px;
  }
}

h4 {
  font-size: 1.5rem;
  text-align: center;
  margin: 5%;
}

img {
  border-radius: 20px;
}

footer {
  padding: 6rem;
  background-color: #000000;
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  align-items: center;
  color: #8003FD;
  margin-top: 4%;
}
.icones{
  
  height: 1.2rem;
}
</style>
