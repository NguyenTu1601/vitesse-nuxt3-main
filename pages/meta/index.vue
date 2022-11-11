<script setup lang="ts">

const router = useRouter()
const p1 = () => {
    router.push({
        path: '/meta/1',
        query: { 
            t: 'a', 
            d: "b", 
            i:"c" 
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