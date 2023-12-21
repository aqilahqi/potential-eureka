<script setup>
import HelloWorld from './components/HelloWorld.vue'
import QuestionTwo from './components/QuestionTwo.vue';
import QuestionThree from './components/QuestionThree.vue';
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="Vue Assessment" />
    </div>
  </header>

  <main>
    <QuestionTwo />
    <QuestionThree />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
  padding-bottom: 20px;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
    padding-bottom: 0;
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
