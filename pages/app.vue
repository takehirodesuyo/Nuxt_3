<script setup>
import { onMounted } from "@vue/runtime-core";
import { ref } from "vue";

const message = "Hello";
</script>

<template>
  <div>
    <div>{{ message }}</div>
    <router-link to="/">index</router-link>
  </div>
</template>

<style>
</style>
