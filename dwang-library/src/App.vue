<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import JSON from './components/JSON.vue'
import Form from './components/Form.vue'
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header> -->

  <main class="page-center">
    <!-- <TheWelcome /> -->
    <!-- <JSON /> -->
    <Form />
  </main>

</template>

<style scoped>

.page-center {
  min-height: 100vh;            /* take full viewport height */
  display: flex;                /* flexbox centering */
  align-items: center;          /* vertical center */
  justify-content: center;      /* horizontal center */
}

header {
  line-height: 1.5;
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
