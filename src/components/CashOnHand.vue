<template>
  <div class="cash-on-hand">
    <h3>Cash on Hand</h3>
    <h1>$ 92,000</h1>
    <h4>Saved 25%</h4>
  </div>
</template>

<script>
export default {
name: "cash-on-hand"
}
</script>

<style scoped>

.cash-on-hand{
 color: white;
  background: linear-gradient(rgb(137, 107, 219), rgb(169, 132, 212))  ;
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