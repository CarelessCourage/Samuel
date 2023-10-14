<script setup lang="ts">
import { umbra } from "@umbrajs/core"

onMounted(() => {
  if(!process) return
  umbra({
    background: "#0c0915",
    foreground: "#c0aea3",
    accents: ["#c97074", "#a9ff00"],
  }).apply()
})
</script>

<template>
  <Hero />
</template>

<style lang="scss">
@import "./css";
</style>