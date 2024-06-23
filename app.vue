<template>
  <div>
    <nuxt-loading-indicator />
  </div>
</template>

<script lang="ts" setup >
const runtimeConfig = useRuntimeConfig()
const appConfig = useAppConfig()

console.log(runtimeConfig)
console.log({appConfig})
// console.log({appConfig})

////
</script>