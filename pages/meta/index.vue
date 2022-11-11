<script setup lang="ts">

const router = useRouter()
const p1 = () => {
    router.push({
        path: '/meta/1',
        query: { 
            t: 'TicketNhuQuynh', 
            d: 'NhuQuynhShow', 
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