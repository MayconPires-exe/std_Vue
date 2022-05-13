<template>
  <h1>olá mundo</h1>
  <h2>Primeiro projeto Vue 3</h2>
</template>

<script lang="ts">

  import { defineComponent } from "vue";

  export default defineComponent({
    name: "OlaMundo"
  })

</script>

<style>
  h1, h2 {
    text-align: center;
    color: #c56363;
  }
</style>