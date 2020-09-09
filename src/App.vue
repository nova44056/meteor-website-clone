<template>
  <div id="app">
    <div class="navbar">
      <navbar/>
    </div>
    <div class="homepage">
      <homepage/>
      <bottompage/>
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
import bottompage from './components/bottompage'
export default {
  components: {
    navbar,
    homepage,
    footerbar,
    bottompage
  }
}
</script>

<style scoped>
/* html{
  margin: 0;
  padding: 0;
} */
.navbar{
  padding-left: 10px;
  padding-right: 10px;
  
}
.homepage{
  height: 100%;
  width:100%;
}
</style>
