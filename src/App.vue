<script setup>
import { ref } from 'vue';
const num = ref(2);
function ClickMe() {
  num.value++
}

</script>

<template>
  <div>
    {{ num }}
  
    <button type="button" v-on:click="ClickMe">點我</button>
  </div>
</template>

