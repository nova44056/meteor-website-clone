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
.navbar{
  padding-left: 20px;
  padding-right: 20px;
  display: flex;
  justify-content: center;
}
</style>
