<template>
<div class="post-card">
    <h3>Titulo</h3>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus nam animi debitis ea deserunt maxime quas, ipsam, reprehenderit dolores vitae nihil. Pariatur repellat repellendus labore quia voluptates, aut eligendi totam.</p>
    <PostButton/>
</div>
</template>

<script lang="ts" setup>
import PostButton from './PostButton.vue';
</script>

<style scoped>
.post-card{
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #ccc;
}
</style>