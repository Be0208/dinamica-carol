<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper"></div>
  </header>

  <header>
    <nav class="navbar">
      <h1 class="logo">Feedback de Equipe</h1>
      <ul class="nav-links">
        <li><a href="#cards">Ver Cards</a></li>
        <li><a href="#submit-feedback">Enviar Feedback</a></li>
        <li><a href="#about">Sobre</a></li>
      </ul>
    </nav>
    
  </header>

  <RouterView />
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #f9f9fc;
}

header {
  background-color: #4caf50;
  color: white;
  padding: 20px 0;
  text-align: center;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 50px;
}

.logo {
  font-size: 28px;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
}

.nav-links li {
  margin-left: 20px;
}

.nav-links a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

.header-content {
  margin-top: 20px;
  text-align: center;
}

.header-content h2 {
  font-size: 36px;
  margin-bottom: 10px;
}

.header-content p {
  font-size: 20px;
  margin-bottom: 20px;
}
</style>
