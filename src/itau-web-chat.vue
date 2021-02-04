<template>
  <div class="hello">
      <h1>Hello Word</h1>
  </div>
</template>

<script>
export default {
  name: 'ItauWebChat',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.hello {
  color: red;
  font-size: 40px;
}
</style>