<script setup lang="ts"></script>

<template>
  <main>
    <div class="cards">
      <div class="card">
        <img src="https://via.placeholder.com/60" alt="Foto de Perfil" class="profile-pic" />
        <div class="card-content">
          <h2>Gustavo Cortezia</h2>
          <p>- cortês<br />- cooperatividade<br />- liderança</p>
        </div>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/60" alt="Foto de Perfil" class="profile-pic" />
        <div class="card-content">
          <h2>Bernardo Dartora</h2>
          <p>- humildade<br />- empenho<br />- serenidade</p>
        </div>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/60" alt="Foto de Perfil" class="profile-pic" />
        <div class="card-content">
          <h2>Alexsandro da Rocha</h2>
          <p>- bom ouvinte<br />- seriedade<br />- trabalho em equipe</p>
        </div>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/60" alt="Foto de Perfil" class="profile-pic" />
        <div class="card-content">
          <h2>Daniel Gheno</h2>
          <p>- criativo<br />- caridoso<br />- comunicação assertiva</p>
        </div>
      </div>
    </div>
  </main>
</template>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f9f9fc;
}

.cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    display: flex;
    align-items: center;
    width: 350px;
    padding: 15px;
    background-color: white;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    border-radius: 12px;
    transition: transform 0.2s ease;
}

.card:hover {
    transform: scale(1.03);
}

.profile-pic {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    object-fit: cover;
    margin-right: 15px;
}

.card-content {
    display: flex;
    flex-direction: column;
}

.card-content h2 {
    margin-bottom: 8px;
    font-size: 20px;
    color: #333;
}

.card-content p {
    font-size: 16px;
    color: #666;
}

</style>
