<template>
  <div class="body">
    <div class="menu">
      <img src="../../assets/images/logo.png" alt="" />
    </div>

    <form action="" method="POST" class="loginForm" v-on:submit.prevent="sendlogin()">
      <input type="text" id="input1" class="inputs" required placeholder="Usuario" />
      <input type="password" name="senha"  class="inputs"  id="input2" required placeholder="Senha"/>
      <button type="submit">Enviar</button>
    </form>

    <div class="rodape">
      <p>Dúvidas? Ligue 0800-761-4631</p>

      <div class="linhas">
        <section class="linha1">
          <h1>Perguntas frequentes</h1>
          <h1>Centro de ajuda</h1>
        </section>

        <section class="linha2">
          <h1>Termos de uso</h1>
          <h1>Privacidade</h1>
        </section>
        <section class="linha3">
          <h1>Preferências de cookies</h1>
        </section>
        <section class="linha4">
          <h1>Informações corporativas</h1>
        </section>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style lang="css" scoped>
@import '@/pages/login.css';
</style>
