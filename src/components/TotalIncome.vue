<template>
  <div class="total-income">
    <h3>Total Income</h3>
    <h1>$ 579,000</h1>
    <h4>Saved 25%</h4>
  </div>
</template>

<script>
export default {
name: "total-income"
}
</script>

<style scoped>

.total-income{

   color: white;
  background: linear-gradient(to right, rgb(87, 98, 201), rgb(228, 132, 212));
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
    line-height: .1vw;
}

</style>