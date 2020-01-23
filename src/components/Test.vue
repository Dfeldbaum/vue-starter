<template>
  <div class="test">test</div>
</template>

<script>
export default {
  name: 'Test',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .test {
    color: red;
    background: blue;
  }
</style>
