<template>
  <div class="section-nav-info">
    <div class="nav-info">
      <img src="assets/IMG_1422.JPG" alt="Foto perfil de Carolina"  width="150px">
      <h2>Carolina Inglethe</h2>
      <h3>Desenvolvedora Web</h3>
    </div>
    <div class="nav-routes-links">
      <p>Sobre mim </p>
      <p>Projetos</p>
      <p>Contato e Redes Sociais</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Informations-nav-bar',
  components: {
  },
};
</script>

<style>
  .section-nav-info {
    background-color: rgb(61, 76, 134);
    display: flex;
    flex-direction: column;
    height: 700px;
    width: 250px;
  }
  .nav-info {
    margin: 15px 25px;
  }
  .nav-routes-links {
    margin: 20px 40px;
  }
</style>
