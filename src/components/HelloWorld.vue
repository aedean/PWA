<template>
  <div class="hello">
    <p>
      <a href="https://www.staffs.ac.uk" target="_blank" rel="noopener">{{ msg }}</a>.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
a {
  color: rebeccapurple;
}
</style>
