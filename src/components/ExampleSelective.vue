<template>
    <h1 v-if="age < 18">Eres menor de edad. Tienes {{ age  }} años</h1>
    <h1 v-else-if="age > 18">Eres mayor de edad. Tienes {{ age }} años</h1>
    <h1 v-else>No se encontro su edad</h1>
    <h2 v-show="age">Tienes {{ age }} años</h2>

    
    
</template>

<script lang="ts" setup>
    let age = 15
</script>

<style scoped>
</style>