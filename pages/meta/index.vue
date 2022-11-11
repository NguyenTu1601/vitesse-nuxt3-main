<script setup lang="ts">

const router = useRouter()
const p1 = () => {
    router.push({
        path: '/meta/1',
        query: { 
            t: 'LIVESHOW THE BEST OF NHƯ QUỲNH |12.11.2022| NHÀ HÁT HOÀ BÌNH', 
            d: 'LIVESHOW THE BEST OF NHƯ QUỲNH là cột mốc đánh dấu 30 năm ca khúc người tình mùa đông', 
            i: 'https://images.tkbcdn.com/1/1560/600/Upload/eventcover/2022/10/25/829FD9.jpg'
        },
    })
}
</script>

<template>
    <!-- <NuxtLink to="/meta/1?t=sdf&d=das">
        Page 1
    </NuxtLink> -->
    <div @click="p1">page 1</div>
</template>