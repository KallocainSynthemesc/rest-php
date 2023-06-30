<script setup>
import RestClient from "@/components/interactive/RestClient.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">RESTful - Sorting</div>
    <div class="content">
      <p>
        Le tri des données est une fonctionnalité intéressante pour une API.
        Pensez au tri comme à ORDER BY dans votre base de données. L'exemple
        ci-dessous montre comment trier par email dans l'ordre ascendant.
      </p>
      <RestClient
        link="https://jsonplaceholder.typicode.com/users?_sort=email"
      ></RestClient>
    </div>
  </div>
</template>

<style scoped></style>
