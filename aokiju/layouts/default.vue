<script setup lang="ts">

</script>

<template>
    <header>
        <NuxtLink to="/"><h1>Aokiju Labo Ver.2.0</h1></NuxtLink>
    </header>

 <!-- 下記slotは、NuxtLayoutコンポーネントの子要素に差し代わる -->
    <slot />

    <footer>
        <NuxtLink to="/"><input type="button" class="abutton" value="Home"/></NuxtLink>
        <h3>©2024 Aokiju Labo</h3>
    </footer>
</template>

<style>

*{
    width: auto;
    height: auto;
}

a{
    color:#1aff00;
    text-decoration:none;
}

a:visited{
    color:#1aff00;
}

a:hover{
    color:#fff;
}

header {
    width: auto;
    height: auto;
    margin-left: -1rem;
    margin-right: -1rem;
    margin-top: -1.5rem;
    padding:1rem;
    text-align: center;
    background-color: #000;
    color:#1aff00;

}

.abutton{
    width: 4rem;
    height: 2rem;
    background-color: #1aff00;
    border:none;
    border-radius: 0.5rem;
}

.abutton:hover{
    background-color: #fff;
}

footer {
    width: auto;
    height: auto;
    margin-left: -1rem;
    margin-right: -1rem;
    margin-bottom: -1.5rem;
    padding:1rem;
    text-align: center;
    background-color: #000;
    color:#1aff00;

}

</style>