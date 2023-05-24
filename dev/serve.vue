<script>
import Vue from 'vue';
import VuePagin8 from '@/vue-pagin8.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VuePagin8
  }
});
</script>

<template>
  <div id="app">
    <vue-pagin8 />
  </div>
</template>
