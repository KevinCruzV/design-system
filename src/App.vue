<script setup>


import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
import Card from './components/molecules/Card.vue'



</script>

<template>
  <header>

    <!-- <div class="wrapper">
      <nav>
        <ul>
          <li>
            <RouterLink to="/">Home</RouterLink>
          </li>
          <li>
            <RouterLink to="/signin">SignIn</RouterLink>
          </li>
        </ul>
      </nav>
    </div> -->
  </header>

  <RouterView />

  <main>
    <Card></Card>
  </main>
</template>

<style scoped>

</style>
