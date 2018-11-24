<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>This is an squirell Octicon&nbsp;
      <octicon name="squirrel" scale="2"></octicon>
    </p>
    <button type="button" name="button" class="btn btn-primary">This is a bootstrap button</button>
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
</style>
