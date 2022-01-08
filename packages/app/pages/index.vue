<template>
  <div>
    <my-button label="Button" primary />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import MyButton from '@ui/src/components/Button/Button.vue'
import { defineComponent, onMounted } from '@nuxtjs/composition-api'

export default defineComponent({
  components: { MyButton },
  name: 'IndexPage',
  setup() {
    onMounted(() => {
      console.log('Mounted')
    })
  }
})

</script>
