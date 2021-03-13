<template lang="pug">
  .container
    Test
    include templates/test
</template>

<script>
import Test from 'components/Test';

export default {
  components: {
    Test
  },
}
</script>

<style lang="sass">
@use 'styles'
</style>
