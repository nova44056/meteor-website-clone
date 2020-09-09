<template>
  <div id="app">
    <div class="navbar">
      <navbar/>
    </div>
    <div class="homepage">
      <homepage/>
    </div>
    <div>
      <footerbar/>
    </div>
  </div>
</template>

<script>
import navbar from './components/navbar'
import homepage from './components/homepage'
import footerbar from './components/footerbar'
export default {
  components: {
    navbar,
    homepage,
    footerbar
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
.homepage{
  height: 100%;
  width:100%;
}
</style>
