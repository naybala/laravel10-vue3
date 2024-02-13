<script setup>
    import { ref } from 'vue'

    const count = ref(0)
</script>

<template>
    <h5>Ha ha</h5>
    {{ count }}

    <button @click="count++">
        Add
    </button>
</template>
