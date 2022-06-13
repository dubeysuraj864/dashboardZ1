<template>
  <div class="app">
    <div class="left-panel">
      <Navbar />
    </div>
    <div class="right-content">
      <Header class="header" />
      <div class="right-bottom">
        <TotalIncome />
        <TotalExpences />
        <CashOnHand />
        <NetProfit />
        <bar/>
        <CircleProgress/>
      </div>


    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Header from "@/components/Header.vue";
import TotalIncome from "@/components/TotalIncome.vue";
import TotalExpences from "@/components/TotalExpences.vue";
import CashOnHand from "@/components/CashOnHand.vue";
import NetProfit from "@/components/NetProfit.vue";
import Bar from "@/components/Bar.vue";
import CircleProgress from "@/components/CircleProgress.vue"

export default {
  name: "App",
  components: {
    Navbar,
    Header,
    TotalIncome,
    TotalExpences,
    CashOnHand,
    NetProfit,
    Bar,
    CircleProgress,

  },
};
</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}
.app {
  background: rgb(240, 240, 240);
  display: flex;
  justify-content: space-between;

  .right-bottom {
    display: flex;
    padding: 1vw;
    flex-wrap: wrap;
    justify-content: center;
    background: white;
    border-radius: 1vw;
    margin-right: 2vw;
  }
}
</style>
