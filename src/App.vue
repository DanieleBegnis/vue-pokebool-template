<script>
import axios from 'axios';
import { store } from './store.js';
import HelloWorld from './components/HelloWorld.vue'

export default {
  components: {
    HelloWorld
  },
  data(){
    return {
      store
    }
  },
  methods: {
  }
}
</script>

<template>
  <HelloWorld></HelloWorld>
</template>

<style lang="scss">
  @use './style/generic.scss';
  @use './style/partials/variables' as *;


</style>
