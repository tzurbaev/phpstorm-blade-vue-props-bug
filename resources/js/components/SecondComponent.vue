<template>
    <p>SecondComponent: {{ names }}</p>
</template>

<script setup>
import { computed } from 'vue';

const props = defineProps({
    items: {
        required: true,
        type: Array,
    },
});

const names = computed(() => props.items.map((item) => item.name).join(', '));
</script>
