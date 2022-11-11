<script setup lang="ts">
const route = useRoute()
console.log(route.query.t)
console.log(route.query.d)
console.log(route.query.i)

useHead({
  title: 'My App',
  meta: [
    { property: 'og:title', content: route.query.t?.toString() },
    { property: 'og:description', content: route.query.d?.toString() },
    { property: 'og:image', content: route.query.i?.toString() },
  ],
})
</script>

<template>
    page
</template>