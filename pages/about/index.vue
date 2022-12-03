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
      </ul>
    </nav>

    <h1>About Page</h1>
  </div>
</template>

<script setup>
</script>

<style lang="scss" scoped>
</style>