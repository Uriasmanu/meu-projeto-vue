<script setup>

let exibir = false;

let media = 3;

</script>

<template>
    <h1 v-if="exibir">ola</h1>
    <p v-if="media >= 7">aprovado</p>
    <p v-else-if="media >= 5">em exame</p>
    <p v-else>reprovado</p>
</template>

