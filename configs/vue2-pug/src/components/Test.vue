<template lang="pug">
  div
    include ../templates/test
    img(:src="logo" alt="logo")
    p.test Hello!
</template>

<script>
import logo from 'img/logo.svg';

export default {
  data() {
    return {
      logo,
    }
  }
}
</script>
