<template>
  <div id="app">
    <FormLogin/>
  </div>
</template>

<script>

import FormLogin from "@/components/login/FormLogin";
export default {
  name: 'App',
  components: {FormLogin}
}
</script>

<style>
*, html, body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background: #eaeaea;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
