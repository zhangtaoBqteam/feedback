<template>
  <div id="app">
    <undo />
    <undo2 />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Undo from './assets/undo.svg'
import Undo2 from '../public/undo.svg'

export default defineComponent({
  name: 'App',
  components: {
    Undo,
    Undo2
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
