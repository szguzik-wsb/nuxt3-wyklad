<template>
<div>
    {{ $route.params.name }}
</div>
</template>
<script setup>
const route = useRoute();

console.log(route.params.name)
</script>