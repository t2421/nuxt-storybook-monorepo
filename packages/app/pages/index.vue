<template>
  <div>
    <my-button label="Button" primary />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import MyButton from '@ui/src/components/Button/Button.vue'
export default Vue.extend({
  components: { MyButton },
  name: 'IndexPage',
})
</script>
