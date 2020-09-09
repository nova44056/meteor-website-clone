<template>
  <div id="app">
    <div class="navbar">
      <navbar/>
    </div>
  </div>
</template>

<script>
import navbar from './components/navbar'
export default {
  components: {
    navbar
  }
}
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.navbar{
  padding-left: 10px;
  padding-right: 10px;
  display: flex;
  justify-content: center;
}
</style>
