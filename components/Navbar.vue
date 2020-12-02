<template>
  <nav class="nav">
    <div class="nav__container">
      <div class="nav__logo">
        <img src="@/static/quest-ar.png" alt="logo">
      </div>
      <div class="nav__links">
        <a href="/">Главная</a>
        <a href="/game">Игра</a>
        <a href="/quests" class="nav__links_active">Квесты</a>
        <a href="/contacts">Контакты</a>
      </div>
    </div>
  </nav>
</template>

<script>
  export default {
    computed: {
      routes() {
       return  this.$router.options.routes
      }
    },
    created(){
      console.log(this.routes)
    }
  }
</script>
