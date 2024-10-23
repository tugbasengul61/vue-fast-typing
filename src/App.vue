<template>
  <Main/>
  <!-- <Confetti/> -->
</template>

<script>
import Main from '@/components/Main.vue'
import Confetti from "./components/Confetti.vue";

export default {
  name: 'App',
  components: {
    Main,
    Confetti,
  },
  methods: {

  },
};
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

