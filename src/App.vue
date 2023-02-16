<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
import Card from './components/molecules/Card.vue'
</script>

<template>
  <header>
  
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/signin">SignIn</RouterLink>
        <RouterLink to="/resetpassword">Reset</RouterLink>
      </nav>
    </div>
  </header>
  
  <RouterView />

  <main>
    <Card class="container"></Card>
  </main>
</template>

<style scoped>

</style>
