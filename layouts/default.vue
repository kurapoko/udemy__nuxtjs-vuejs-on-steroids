<template>
  <div>
    <Header />
    <nuxt />
  </div>
</template>
<script>
import Header from '~/components/Header.vue'
export default {
  components: {
    Header
  },
  layout: 'users'
}
</script>
<style lang="stylus" scoped>

</style>

