<script setup>
defineProps(["title", "todoItem"]);
</script>

<template>
    <h3 class="category-title">{{title}}</h3>
    <p style="color: white">{{todoItem}}</p>    
</template>

<style scoped>
.category-title {
    color: var(--text-color-light);
    font-weight: 600;
}

.todo-item {
    margin-bottom: 16px;
}
</style>