<template>
  <div class="view">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: "BasicChart",
  props: {
    msg: String
  }
}
</script>

<style lang="css" scoped>
h1 {
  color: red
}
</style>


