<template>
  <div class="grid-container">
      <div class="meteor-logo">
        <img src="../assets/meteor-logo.svg">
      </div>
      <p class="div2">div2</p>
      <p class="div3">div3</p>
      <p class="div4">div4</p>
      <p class="div5">div5</p>
  </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.div2{
    grid-area: 1 / 6 / 2 / 7; 
    display: flex;
    align-items: center;
    justify-content: center;
}
.div3{
    grid-area: 1 / 7 / 2 / 8;
    display: flex;
    align-items: center;
    justify-content: center;
}
.div4{
    grid-area: 1 / 8 / 2 / 9;
    display: flex;
    align-items: center;
    justify-content: center;
}
.div5{
     grid-area: 1 / 9 / 2 / 10;
    display: flex;
    align-items: center;
    justify-content: center;
}
.meteor-logo{
    grid-area: 1 / 1 / 2 / 2;
    display: flex;
    align-items: center;
    justify-content: center;
    padding-bottom: 5px;
}

.meteor-logo img{
    height: 25px;
}

.grid-container {
    /* align-items: center; */
    display: grid;
    grid-template-columns: repeat(9, 1fr);
    grid-template-rows: 1fr;
    grid-column-gap: 0px;
    grid-row-gap: 0px; 
    padding-top: 10px;
    padding-bottom: 10pxs;
}
</style>
