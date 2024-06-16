<template>
  <test1/>
  <SMenu></SMenu>
  <router-view></router-view>
  <back-top></back-top>
  <customer></customer>
  <foot></foot>

</template>

<script setup>
import {RouterView} from 'vue-router'
import SMenu from './components/bar/menu.vue'
import Foot from './components/bar/footer.vue'
import BackTop from "./components/back-top.vue";
import Customer from "./components/customer.vue";
import person123 from './components/test1.vue';
</script>

<style scoped>

</style>
