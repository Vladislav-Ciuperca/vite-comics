<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  components : {
    HelloWorld,
  },

  data () {
    return {
      prova: 'ciao a tutti'
    }
  },
    methods:{
      // placeholder
    },

    mounted () {
      // placehyolder
    }
}

</script>


<template>
  <div>vite dice {{prova}}!</div>
  <HelloWorld/>
</template>