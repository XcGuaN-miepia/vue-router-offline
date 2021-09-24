<script setup>
import { useRouter } from 'vue-router'
const router = useRouter()

function pushTestPage() {
  router.push('/test')
}
</script>

<template>
  <h1>Home Page</h1>
  <button @click="pushTestPage">pushTestPage</button>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
