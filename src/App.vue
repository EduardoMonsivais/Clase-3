<script setup>
import HelloWorld from './components/HelloWorld.vue'
import CounterFile from './components/CounterFile.vue'
</script>

<template>
  <header>
  <HelloWorld />
  <CounterFile />
</header>

<div>
  <img :src="require('@/assets/Familia.jpg')" width="600" />
</div>

</template>
