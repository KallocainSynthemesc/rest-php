<script setup>
import RestClient from "@/components/interactive/RestClient.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">RESTful - Endpoint</div>
    <div class="content">
      <p>
        Les données relatives aux "Todos" de notre application seront
        probablement stockées dans une table "Todos" avec un modèle "Todo". On
        utilise des noms pluriels lorsqu'on a l'URL d'une collection de
        ressources de ressources: GET /todos
      </p>
      <RestClient
        link="https://jsonplaceholder.typicode.com/todos"
      ></RestClient>
    </div>
  </div>
</template>

<style scoped></style>
