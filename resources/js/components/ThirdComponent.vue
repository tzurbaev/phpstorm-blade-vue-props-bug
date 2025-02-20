<template>
    <p>ThirdComponent: {{ year }}</p>
</template>

<script setup>
defineProps({
    year: {
        required: true,
        type: Number,
    },
});
</script>
