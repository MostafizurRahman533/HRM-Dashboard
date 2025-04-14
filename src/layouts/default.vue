<template>
  <div>
    <div>
      <div class="flex h-screen">
        <Sidebar />
        <div class="flex-1 flex flex-col overflow-hidden">
          <Topbar />
          <slot />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
  import Sidebar from '../components/Sidebar.vue';
  import Topbar from '../components/Topbar.vue';
</script>

<style scoped></style>
