<script setup>
    let lista = ["ana", "ana", "ana", "ana"];
</script>

<template>
    <ul>
      <li v-for="(nome,index) in lista" :key="index">{{ nome }}</li>
    </ul>
  </template>