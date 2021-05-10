<template>
  <div>
    <p> {{ msg }} </p>
  </div>
</template>

<script setup>
import { defineProps } from 'vue';
defineProps({ msg: String });
</script>

<style scoped>
a {
  color: #42b983;
}
p {
  color: #2c3e50;
  font-weight: 700;
  font-size: 24px;
  letter-spacing: -1px;
}
</style>