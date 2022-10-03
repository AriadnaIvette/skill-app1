<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="skills app" class="logo" src="./assets/Skills app logo.jpeg" width="125" height="125" />
  <h1>
  Bienvenido/bienvenida a tu Skills app
  </h1>

    <div class="wrapper">
      <HelloWorld msg="Skills app" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  margin-block-end: 300px;
}

.logo {
  display: grid;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin-top: 0px;
    margin-left: 0px;
    margin-bottom: 0px;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
    margin-bottom: auto;
    margin-left: 1px;
  }
}

h1{
  color:rgb(58, 100, 100);
  margin: auto;
  display: flex;
  margin-left: auto;
}
</style>
