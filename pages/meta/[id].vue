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
    { property: 'og:title', content: "LIVESHOW THE BEST OF NHƯ QUỲNH | 12.11.2022 | NHÀ HÁT HOÀ BÌNH"},
    { property: 'og:description', content: "LIVESHOW THE BEST OF NHƯ QUỲNH là cột mốc đánh dấu 30 năm ca khúc người tình mùa đông" },
    { property: 'og:image', content: i.value?.toString },
  ],
})
</script>

<template>
    page
</template>