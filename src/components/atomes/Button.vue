<template>
    <button class="button" type="button">{{ text }}</button>
</template>

<script>
import { defineProps } from 'vue'

const props = defineProps({
    radius: {
      type: Int16Array,
      required: true
    },
    text: {
        type: String,
        required: true
    },
    state:{
        type: String,
        required: true
    }
})

</script>


<style scoped>
    .button {
    background-color: v-bind(backgroundColor);
    border-radius: v-bind(radius);
    }
</style>