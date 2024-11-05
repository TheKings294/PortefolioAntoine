<script setup>
import logoHome from './icons/logoHome.vue';
import textHome from './icons/textHome.vue';
</script>

<template>
    <div id="NavBar">
        <a href="#"><logoHome></logoHome></a>
        <nav>
            <a href="#">Work</a>            
            <a href="#">CV & About</a>
        </nav>
    </div>
</template>

<style scoped>
#NavBar {
    display: flex;
    align-items: center;
}
nav>a {
    margin-left: 1em;
}
</style>