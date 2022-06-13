<template>
  <div class="total-expences">
    <h3>Total Expences</h3>
    <h1>$ 79,000</h1>
    <h4>Saved 25%</h4>
  </div>
</template>

<script>
export default {
name: "total-expences"
}
</script>

<style scoped>

.total-expences{
 color: white;
  background: linear-gradient(to right, lightskyblue, rgb(46, 167, 243))  ;
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