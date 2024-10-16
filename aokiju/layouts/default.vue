<script setup lang="ts">

</script>

<template>
    <header>
        <NuxtLink to="/"><h1>Aokiju Labo Ver.2.0</h1></NuxtLink>
    </header>

 <!-- 下記slotは、NuxtLayoutコンポーネントの子要素に差し代わる -->
    <body>
        <slot />
    </body>

    <footer>
        <NuxtLink to="/"><input type="button" class="abutton" value="Home"/></NuxtLink>
        <h3>©2024 Aokiju Labo</h3>
    </footer>
</template>