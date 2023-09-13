<script setup lang="ts">
let name = ref("");
let pass = ref("");
</script>

<template>
  <div>Login</div>
  <div>
    <input type="enter name" v-model="name" />
    <br>
    <input type="enter password" v-model="pass" />
  </div>
</template>

<style scoped></style>
