<template>
  <div>
    <i-display :code="code"></i-display>
  </div>
</template>

<script>
import iDisplay from '../components/display/display.vue';
import defaultCode from './default-code.js';
export default {
  name: 'Display',
  components: { iDisplay },
  data () {
    return {
      code: defaultCode
    }
  }

}
</script>

<style>
</style>