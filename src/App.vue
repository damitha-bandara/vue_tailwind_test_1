<script setup>
import { RouterView } from 'vue-router'
import navbar from '@/components/navbar.vue';
import footers from './components/footer.vue';

</script>

<template>
  <navbar />  <!--this is render for all pages navbar -->

  <RouterView />  <!--this is render for all pages body -->

  <footers /> <!--this is render for all pages footer -->
</template>