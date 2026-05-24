<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <h1 class="font-bold text-center"> Добро пожаловать на сайт про машины </h1>
    <div class="wrapper">

      <nav class="px-3 flex items-center gap-2 border-b border-gray-200 py-2">
        <RouterLink class="cursor-pointer font-bold" to="/">Главная</RouterLink>
        <RouterLink  class="cursor-pointer font-bold" to="/about">Информация о сайте</RouterLink>
        <RouterLink  class="cursor-pointer font-bold" to="/props">Марки машин</RouterLink>

      </nav>
    </div>
  </header>

  <RouterView />
</template>


