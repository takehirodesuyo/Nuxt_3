<script setup>
const index = "index";
definePageMeta({
  layout: "authenticated",
});
</script>

<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
    <div>{{ index }}</div>
    <h1>router</h1>
    <router-link to="/app">app page</router-link>
  </div>
</template>