<template>
    <p>FirstComponent: {{ name }}</p>
</template>

<script setup>
defineProps({
    name: {
        required: true,
        type: String,
    },
});
</script>
