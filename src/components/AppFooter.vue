<script>
import FooterUp from './FooterUp.vue';
import FooterMid from './FooterMid.vue';
import FooterDown from './FooterDown.vue';

export default {
  components: {
    FooterUp,
    FooterMid,
    FooterDown,
  },
  data() {
    return {
      messaggino: 'sonon il figlio'
    }
  },
  methods: {
    // placeholder
  },

  mounted() {
    // placehyolder
  }
}
</script>

<template>
  <FooterUp />
  <FooterMid />
  <FooterDown />
</template>