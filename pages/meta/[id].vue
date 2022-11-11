<script setup lang="ts">
const route = useRoute()
console.log(route.query.t)
console.log(route.query.d)
console.log(route.query.i)

const t = ref(route.query.t)
const d = ref(route.query.d)
const i = ref(route.query.i)

useHead({
  title: 'My App',
  meta: [
    { property: 'og:title', content: t.value?.toString},
    { property: 'og:description', content: d.value?.toString },
    { property: 'og:image', content: i.value?.toString },
  ],
})
</script>

<template>
    page
</template>