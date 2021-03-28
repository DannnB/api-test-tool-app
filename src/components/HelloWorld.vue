<template>
  <div class="Login">
    <h1>{{ msg }}</h1>
    <form>
      <label>
        Username or Email
        <input type="text"/>
      </label>
      <label>
        Password
        <input type="password"/>
      </label>
    </form>
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
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
