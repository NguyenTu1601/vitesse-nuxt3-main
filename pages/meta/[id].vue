<script setup lang="ts">
import { json } from 'stream/consumers';

const route = useRoute()
console.log(route.query.t)
console.log(route.query.d)
console.log(route.query.i)

useHead({
  title: 'My App',
  meta: [
    { name: 'description', content: "LIVESHOW THE BEST OF NHƯ QUỲNH | 12.11.2022 | NHÀ HÁT HOÀ BÌNH"},
    { name: 'keyword', content: "LIVESHOW THE BEST OF NHƯ QUỲNH | 12.11.2022 | NHÀ HÁT HOÀ BÌNH"},
    { property: 'og:title', content: "LIVESHOW THE BEST OF NHƯ QUỲNH | 12.11.2022 | NHÀ HÁT HOÀ BÌNH"},
    { property: 'og:description', content: 'LIVESHOW THE BEST OF NHƯ QUỲNH là cột mốc đánh dấu 30 năm ca khúc người tình mùa đông'},
    { property: 'og:image', content: 'https://images.tkbcdn.com/1/1560/600/Upload/eventcover/2022/10/25/829FD9.jpg' },

  ],
})
</script>

<template>
    page
</template>