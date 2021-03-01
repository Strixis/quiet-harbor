<template>
  <div>
    <img :src="logo" alt="logo">
    <p class="test">Hello!</p>
  </div>
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
