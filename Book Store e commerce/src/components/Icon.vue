<script setup>
    defineProps({
        labelUrl: {
            type: String,
            required: true,
        },
        desc: {
            type: String,
            required: true,
        }
    })
</script>

<template>
    <div class="flex h-auto items-center">
        <img class="w-[22px] h-[22px]" :src="labelUrl" alt="">
        <span class="pl-[8px]">{{ desc }}</span>
    </div>
</template>