<template>
  <div class="app-wrapper">
    <AppHeader />

    <main class="main-content">
      <RouterView />
    </main>
  </div>
</template>

<script setup lang="ts">
import AppHeader from './components/AppHeader.vue'
</script>

<style scoped>
.app-wrapper {
  min-height: 100vh;
  background: #f8fafc;
}

.main-content {
  width: 100%;
}
</style>