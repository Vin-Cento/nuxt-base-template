<script setup lang="ts">
let name = ref("Vincent");
</script>

<template>
  <div>current name: {{ name }}</div>
  <div>
    <input type="enter name" v-model="name" />
  </div>
</template>

<style scoped></style>
