
<script setup>
import Header from "./components/Header.vue";


import { RouterView } from "vue-router";
</script>

<template>
    <div class="app">
        <Header />
        <RouterView />
    </div>
</template>

<style scoped>
.app {
    background: #272b30;
    min-height: 100vh;
}
</style>
