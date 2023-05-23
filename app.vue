<template>
  <div>
      <HomeLanding/>
  </div>
</template>

<script setup lang="ts">
const { $gsap } = useNuxtApp()

onMounted(() => {
  $gsap.to('h1', { rotation: 3, x: 100, duration: 1 })
})
</script>