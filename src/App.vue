<script setup></script>
<template>
  <keep-alive include="left">
    <left></left>
  </keep-alive>
  <keep-alive>
    <right></right>
  </keep-alive>
</template>
<script setup>
import left from "./views/left.vue";
import right from "./views/right.vue";
</script>
<style></style>
