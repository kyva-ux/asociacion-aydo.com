<template lang="pug">
NuxtLink.btn(:to='link')
  slot
</template>

<script setup>
const props = defineProps([
  'link'
])
</script>

<style>
.btn {
  margin-top: 24px;
  background: #4f5252;
  color: white;
  border-radius: 10px;
  display: inline-block;
  padding: 8px 48px;
  font-weight: 500;
  cursor: pointer;
  transition: all .2s ease-in-out;
  box-shadow: 0px 2px 12px rgba(0, 0, 0, .4);
}

.btn:hover {
  background: #616666;
  transform: translateY(-2px);
  box-shadow: 0px 2px 16px rgba(0, 0, 0, .5);
}

.btn:active {
  transform: translateY(0px);
  box-shadow: none;
}
</style>
