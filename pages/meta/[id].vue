<script setup lang="ts">
import { json } from 'stream/consumers';

const route = useRoute()
console.log(route.query.t)
console.log(route.query.d)
console.log(route.query.i)

useHead({
  title: 'My App',
  meta: [
    { property: 'og:title', content: "LIVESHOW THE BEST OF NHƯ QUỲNH | 12.11.2022 | NHÀ HÁT HOÀ BÌNH"},
    { property: 'og:description', content: JSON.stringify(route.query.t)},
    { property: 'og:image', content: 'https://images.tkbcdn.com/1/1560/600/Upload/eventcover/2022/10/25/829FD9.jpg' },

  ],
})
</script>

<template>
    page
</template>