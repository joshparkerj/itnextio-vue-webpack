<template>
  <div class="hello">
    <h1>Hello {{ name }}!</h1>
  </div>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      required: true
    }
  }
};
</script>

<style lang="stylus" scoped>
.hello h1 {
  color: red;
}
</style>
