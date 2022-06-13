<template>
  <div class="net-profit">
    <h3>Net Profit Margin</h3>
    <h1>$ 179,000</h1>
    <h4>Saved 25%</h4>
  </div>
</template>

<script>
export default {
name: "net-profit"
}
</script>

<style scoped>

.net-profit{
   color: white;
  background: linear-gradient(to right, rgb(91, 194, 159), rgb(9, 172, 212))  ;
  width: 30vw;
  display: flex;
  justify-content: center;
  align-items: left;
  flex-direction: column;
     border-radius: 1vw;
    margin: 2vw;
    padding: 1vw 0vw;
    
}
h3,h1,h4{
    margin-left: 2vw;
    line-height: .4vw;
}

</style>