<template>
  <!-- <div>
    custom
    <NuxtPage />
  </div> -->
  <div>
    <NuxtLayout name="custom">
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: false,
});
</script>

<style scoped></style>
