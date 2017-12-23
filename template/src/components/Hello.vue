<template>
<div v-html="message"></div>
</template>

<script>
export default {
  data: () => ({}),

  computed: {
    message() {
      return this.$store.state.message
    }
  }
}
</script>

<style lang="css">

</style>
