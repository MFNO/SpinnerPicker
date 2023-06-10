<script setup lang="ts">

</script>

<template>
  <div class="full-width row wrap justify-center items-start content-center">
    <div style="overflow: auto;" class="column content-center col-6">
      <h5 style="text-align:center">Spinner</h5>
      <div class="spinner"></div>
    </div>
    <div style="overflow: auto;" class="column content-center col-6">
      <h5>Names</h5>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.spinner {
  width: 400px;
  height: 400px;
  background-image: conic-gradient(orange 64%, blue 17%, black);
  border-radius: 50%
}
</style>
