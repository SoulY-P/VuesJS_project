<script setup>
    import {ref} from 'vue';
    const counter = ref(0);
</script>

<template>
  <main>
    <div>
    <h4>Counter now is...</h4>
    <h1>{{counter}}</h1>
    <div id="button">
    <button @click="counter--">-</button>
    <button @click="counter++;">+</button>
    </div></div>
  </main>
</template>

<style scoped>
main{width: 100vw; height: 100vh; display: flex; justify-content: center; align-items: center; flex-flow: column nowrap; text-align: center;}
#button{display: flex; justify-content: space-evenly;}
</style>
