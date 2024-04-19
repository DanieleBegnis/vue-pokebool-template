<script>
import axios from 'axios';
import { store } from './store.js';
import HelloWorld from './components/HelloWorld.vue'

//URL da chiamare  https://raw.githubusercontent.com/Biuni/PokemonGO-Pokedex/master/pokedex.json'

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
