<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router/auto'
</script>

<template>
  <header>
    <nav>
      <ul>
        <li>
          <RouterLink to="/" class="text-red-500 underline"> Accueil </RouterLink>
        </li>
      </ul>
    </nav>
  </header>
  <Suspense>
    <routerView />
  </Suspense>
</template>
