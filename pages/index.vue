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
          <!-- Group routing -->
          <NuxtLink
            :to="{name : 'users-role-id', params : { role : 'admin' , id : 123}}"
          >Group Routing 123</NuxtLink>
        </li>
      </ul>
    </nav>
    <h2>
      Welcome to
      <span class="text-green">Nuxt 3 Practice App</span>
    </h2>
  </div>
</template>

<script setup>
</script>

<style lang="scss" scoped>
h2 {
  color: greenyellow;
  span: {
    color: red;
  }
}
</style>