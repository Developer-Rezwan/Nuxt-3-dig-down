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
          <!-- <NuxtLink :to="{name : 'about' , params : {id : 123 }}">About 123</NuxtLink> -->
        </li>
      </ul>
    </nav>
    <h2>
      Welcome to homepage
      <h3>hello</h3>
    </h2>
  </div>
</template>

<script setup>
</script>

<style lang="scss" scoped>
h2 {
  color: greenyellow;
  h3 {
    color: red;
  }
}
</style>