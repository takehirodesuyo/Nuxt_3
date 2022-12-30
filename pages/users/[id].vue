<script setup>
const route = useRoute();

const message = "/users/_id.vueを表示";
const id = route.params.id;

onMounted(() => {
  validate(id);
});
</script>

<template>
  <section>
    <h1>
      {{ message }}
    </h1>
    <p>id: {{ $route.params.id }}</p>
    <p>{{ id }}</p>
  </section>
</template>