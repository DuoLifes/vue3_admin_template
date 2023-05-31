<template>
  <div style="height:1000px">
<iframe :src="src" frameborder="0" style="width: 100%;height: 100%;"></iframe>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';
let src = ref('../../../../3Drotate/index.html')

</script>

<style scoped></style>