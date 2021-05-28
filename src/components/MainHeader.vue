<template>
  <header>
    {{headerText}}
  </header>
</template>

<script>
export default {
  name: 'MainHeader',
  props: {
    headerText: String
  }
}
</script>

<style scoped>
header {
  background: aliceblue;
  width: 100vw;
  padding: 30px 0;
}
</style>