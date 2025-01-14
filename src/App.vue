<template>
  <div class="container">
    <div class="row">
      <base-header />
    </div>
    <div class="row">input</div>
    <div class="row"><router-view /></div>
  </div>
</template>

<script lang="ts" setup>
import BaseHeader from "@/components/headerItem.vue";
</script>
<style lang="scss">
#app {
  padding: 100px;

  .row + .row {
    margin-top: 15px;
  }
}
</style>
