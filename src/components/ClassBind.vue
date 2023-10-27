<template>
<p v-bind:class="{
    'danger' : hasError,
    'green': hasGreen,
    'blue': hasBlue
}" >El mensaje se ha enviado satisfactoriamente</p>
</template>

<script lang="ts" setup>
            let hasError = false
            let hasGreen = true
            let hasBlue = false
</script>

<style scoped>
.danger{
    color: red;
}

.green{
    color: greenyellow;
}

.blue{
    color: blue;
}
</style>