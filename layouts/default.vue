<template>
  <div>
    <Title class="text-green">Nuxt 3 Practice App</Title>
    <nav>
      <ul>
        <li>
          <NuxtLink :to="{name : 'index'}">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink :to="{name : 'about'}">About</NuxtLink>
        </li>
        <li>
          <NuxtLink :to="{name : 'about-user_id', params : {user_id : 123}}">About 123</NuxtLink>
        </li>
        <li>
          <!-- Group routing -->
          <NuxtLink
            :to="{name : 'users-role-id', params : { role : 'admin' , id : 123}}"
          >Group Routing 123</NuxtLink>
        </li>
      </ul>
    </nav>
    <div>
      <slot />
    </div>
  </div>
</template>

<script setup lang="ts">
</script>

<style scoped>
</style>