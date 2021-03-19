<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from './components/Header'
export default {
  name: 'App',
  components: {
    Header
  }
  
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Commissioner:wght@400;500;600&display=swap');
* {
  box-sizing: border-box;
}

html, body{
  height: 100%;
  padding: 0;
  margin: 0;
  text-align: center;
  font-family: 'Commissioner', sans-serif;
}
</style>
