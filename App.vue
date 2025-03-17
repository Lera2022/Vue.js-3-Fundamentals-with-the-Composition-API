<script setup>
import { ref } from 'vue';


const msg = ref('Hello World!');
</script>

<template>
  <!--  <h1>{{ msg }}</h1>-->
  <h1>{{ msg.toLocaleUpperCase() }}</h1>
  <input v-model='msg'>
  <!--  <input v-model="msg">-->
</template>