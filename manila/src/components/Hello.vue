<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <h2>登他一录！</h2>
    <ul>
      <li><router-link to="/login">登录</router-link></li>

    </ul>

    <h2>进它个大厅！</h2>
    <ul>
      <li><router-link to="/game_hall">进大厅</router-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
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

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
