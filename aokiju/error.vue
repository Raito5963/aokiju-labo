<script setup>
const error = useError();
</script>

<template>
    <NuxtLayout>
        <h1 v-if="error.statusMessage === 404">404 not found</h1>
        <h1 v-else>Error</h1>
        <p>{{ error.message }}</p>
    </NuxtLayout>
</template>