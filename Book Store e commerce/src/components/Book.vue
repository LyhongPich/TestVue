<script setup>
    defineProps({
        url: {
            type: String,
            required: true,
        },
        title: {
            type: String,
            required: true,
        },
        price: {
            type: String,
            required: true,
        }
    })
</script>

<template>
    <div class="text-center w-full h-full flex flex-col justify-center">
        <div class="">
            <img :src="url" alt="">
        </div>
        <div class="">
            <span>{{ title }}</span>
        </div>
        <div class="">
            <span>{{ price }}</span>
        </div>
    </div>
</template>