<script setup>
import { ref } from 'vue';

    let validacao = ref(false);

</script>

<style>
    .ok{color: green;}
    .falha{color: red;}
</style>

<template>
    <p :class="validacao ? 'ok' : 'falha'" >Texto</p>
    <button @click="validacao = !validacao" >aperte</button>
</template>