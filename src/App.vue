<script setup>
import { ref } from 'vue';
const count = ref(0);
</script>
<template>
  <main>
    <div>
      <container class="container">
        <h4>the current count is...</h4>
        <h1>{{count}}</h1>
        <button @click="count--">-</button>
        <button @click="count++">+</button>
      </container>
    </div>
    </main>
</template>

<style scoped>
main{
  background-color: aliceblue;
  height: 100vh;
  width: 100vw;
  display: flex;
  align-items: center;
  justify-content: center;

}
div{
  text-align: center;
}
</style>