<template>
  <HeaderView />
  <RouterView />
  <FooterView />
</template>

<script setup>
import { RouterView } from 'vue-router'
import HeaderView from './components/HeaderView.vue'
import FooterView from './components/FooterView.vue'
</script>
<style scoped></style>
