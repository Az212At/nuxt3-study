<script setup>
import { ref } from "vue";

const posts = ref([
  {
    id: 1,
    title: "Введение в Nuxt 3",
    content: "Основы, преимущества и простая установка.",
  },
  {
    id: 2,
    title: "Советы по оптимизации производительности в Vue",
    content: "Рекомендации и лучшие практики.",
  },
  {
    id: 3,
    title: "Почему стоит изучать JavaScript в 2024 году",
    content: "Тенденции и востребованные навыки.",
  },
])

const route = useRoute()
const post = posts.value.find(p => p.id === Number(route.params.id))
</script>

<template>
  <div>
    <h1>{{ post.title }}</h1>
    <p>{{ post.content }}</p>
    <nuxt-link to="/">На главную</nuxt-link>
  </div>
</template>

<style scoped>
</style>
