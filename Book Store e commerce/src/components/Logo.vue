<script setup>
    defineProps({
        url: {
            type: String,
            required: true,
        }
    })
</script>

<template>
    <img :src="url" alt="" class="w-full h-full">
</template>