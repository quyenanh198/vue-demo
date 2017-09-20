<template>
  <div class="footer">
    <p>{{ msg }}s</p>
  </div>
</template>

<script>
export default {
  name: 'footer',
  data () {
    return {
      msg: 'Copyright @ 2017 by <a href="https://github.com/quyenanh198" target="_blank">Quyen Anh</a>'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}
1
li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
