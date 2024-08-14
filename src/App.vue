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
      <li><img class="pessoa" src="../src/img/perfil.png" alt=""></li>
    </ul>
  </header>

  <section>
    <h4>Oferecemos um atendimento personalizado e orçamentos</h4>
    <p>No Sr. Elvis, estamos comprometidos em oferecer serviços de alta qualidade para atender todas as suas necessidades relacionadas a celulares. Nossa missão é proporcionar soluções rápidas e eficazes, garantindo a melhor experiência para você.</p>
  </section>
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
  .logo{
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
</style>
