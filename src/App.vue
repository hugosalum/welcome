<script setup>
import { RouterLink, RouterView } from "vue-router";
import topside from "./components/topside.vue";
</script>

<template>
    <RouterLink to="/bober" class="bobr">bobr</RouterLink>
</template>

<style scoped>
.bobr {
    color: black;
    background-color: red;
    text-align: center;
    border-radius: 20%;
}
</style>
