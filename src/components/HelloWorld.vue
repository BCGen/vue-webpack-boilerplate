<template>
  <div class="message">
    {{ message }}
  </div>
</template>

<script>
export default {
  data () {
    return {
      message: 'Hello World!!'
    }
  }
}
</script>

<style lang="scss" scoped>
  .message {
    color: blue;
  }
</style>
