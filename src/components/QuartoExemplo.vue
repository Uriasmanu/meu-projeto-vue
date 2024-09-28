<template>
    <input v-model="mensagem" type="text" />
    <p>A mensagem é: {{ mensagem }}</p>
</template>

<script setup>
import { ref } from 'vue';

let mensagem = ref('')
</script>
