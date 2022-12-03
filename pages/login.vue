<template>
  <div>
    <form>
      <div>
        <label for="username">Username</label>
        <input type="text" />
      </div>
      <br />
      <div>
        <label for="password">Password</label>
        <input type="text" />
      </div>
    </form>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: "auth"
});
</script>

<style scoped>
</style>