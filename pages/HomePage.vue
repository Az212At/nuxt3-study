<template>
  <div>
    <h1>Добро пожаловать в блог о технологиях!</h1>
    <p>Здесь вы найдете статьи о Nuxt 3, Vue, JavaScript и других технологиях.</p>
    <h2>Последние статьи:</h2>
    <ul>
      <li>
        <nuxt-link to="/posts/1">
          Введение в Nuxt 3
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/posts/2">
          Советы по оптимизации производительности в Vue
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="/posts/3">
          Почему стоит изучать JavaScript в 2024 году
        </nuxt-link>
      </li>
    </ul>
    <nav>
      <nuxt-link to="/about">О нас</nuxt-link>
    </nav>
  </div>
</template>

<script setup>
</script>

<style scoped>
</style>
