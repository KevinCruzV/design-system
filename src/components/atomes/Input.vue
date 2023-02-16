<template>
    <div>
        <label for="">{{ label }}</label>
        <input />
    </div>
</template>

<script setup>
import { defineProps } from 'vue'
const props = defineProps({
    label: {
        type: String,
        required: true
    },
    state: {
        type: String,
        required: true
    },
    type: {
        type: String,
        required: true
    }
})
</script>