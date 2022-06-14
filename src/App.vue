<script setup>
import PageHeader from "./components/Header.vue";
import PageFooter from "./components/Footer.vue";
import Home from "./components/Home.vue";
</script>

<template>
  <div class="page-main-wrap inner-pages-wrap">
    <page-header> </page-header>
    <home></home>
    <page-footer> </page-footer>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;400;500;600;700;800&display=swap");

@import "./assets/css/animate.css";
@import "./assets/css/fontawesome.min.css";
/* @import './assets/fonts'; */
@import "./assets/css/bootstrap.min.css";
@import "./assets/css/style.css";
</style>
