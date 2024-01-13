<script setup>
import { ref } from "vue";
import { invoke } from "@tauri-apps/api/tauri";


</script>

<template>
  <div class="bar">
    <img class="menu" src="../assets/menu.png" alt="menu">
  </div>
</template>

<style scoped>
.bar {
    --tw-bg-opacity: 1;
    background-color: rgb(251 113 133 / var(--tw-bg-opacity));
    height: 5vh;
    display: flex;
    align-items: center;
}
.menu {
    margin-left: 1rem;
    width: 4vw;
    height: 4vh;
}
</style>
