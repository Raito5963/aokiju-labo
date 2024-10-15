<script setup lang="ts">

</script>

<template>
    <header>
        <h1><a href="/">Aokiju Labo Ver.2.0</a></h1>
    </header>

 <!-- 下記slotは、NuxtLayoutコンポーネントの子要素に差し代わる -->
    <slot />

    <footer>
        <hr />
        <NuxtLink to="/"><input type="button" class="abutton" value="Home"/></NuxtLink>
        <h3>©2024 Aokiju Labo</h3>
    </footer>
</template>

<style>
</style>