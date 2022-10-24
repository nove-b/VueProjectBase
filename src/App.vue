<script setup lang="ts">
import iconUrl from "./assets/vue.svg?url";
import iconRow from "./assets/vue.svg?raw";
import IconComponent from "./assets/vue.svg?component";
</script>

<template>
  <img :src="iconUrl" class="logo vue" alt="Vue logo" />
  <div v-html="iconRow"></div>
  <IconComponent />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
