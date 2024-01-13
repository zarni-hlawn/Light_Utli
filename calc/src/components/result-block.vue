<script setup>
import { ref } from "vue";
import { invoke } from "@tauri-apps/api/tauri";

var previous = ref("...");
var current = ref(0);

</script>

<template>
  <div class="block">
    <div id="previous" class="previous">
        {{ previous }}
    </div>
    <div id="current" class="current">
        {{ current }}
    </div>
  </div>
</template>

<style scoped>
.block {
    background-color:aqua;
    text-align: end;
    height: 20vh;
    
}
.current {
    font-size: 8vw;
    margin-right: 3rem;
}
.previous {
    font-size: 3vw;
    margin-right: 3.5rem;
    opacity: 40%;
}
</style>
