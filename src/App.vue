<template>
  <div id="app">

      <ContentMain/>  
      <FormLogin/>
  </div>
</template>

<script>

import FormLogin from "@/components/login/FormLogin";
import ContentMain from './components/ContentMain.vue';
export default {
  name: 'App',
  components: {
    FormLogin,
    ContentMain
  }
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
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  max-width: 60%;
  margin: 0 auto;
  
}
</style>
