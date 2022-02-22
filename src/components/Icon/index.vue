<template>
  <component :is="name" v-bind="$props" />
</template>

<script>
import Loading from './Loading.vue'

export default {
  components: {
    Loading
  },
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'index',
  props: {
    name: { type: String, required: true }
  }
}
</script>

<style scoped>

</style>
