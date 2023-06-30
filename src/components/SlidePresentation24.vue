<script setup>
import RestClient from "@/components/interactive/RestClient.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">RESTful - Sorting</div>
    <div class="content">
      <p>
        notre api provisoire, par exemple, fonctionne comme dans l'exemple
        ci-dessous
      </p>
      <RestClient
        link="https://jsonplaceholder.typicode.com/users?_page=2&_limit=5"
      ></RestClient>
    </div>
  </div>
</template>

<style scoped></style>
