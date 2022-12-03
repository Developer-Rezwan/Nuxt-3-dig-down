<template>
  <div>
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
      </ul>
    </nav>

    <h1>About Page</h1>
  </div>
</template>

<script setup>
</script>

<style lang="scss" scoped>
</style>