<template>
  <main>
    <div class="left">
      <span>% of Income Budget</span>
      <div class="budget">
        <h1>69%</h1>
      
      </div>
      <circle-progress
        id="circle1"
        :is-gradient="true"
        :gradient="{
          angle: 70,
          startColor: '#03fcb1',
          stopColor: '#00a6ff',
        }"
        style="
          width: 100px;
          padding: 2vw;
          margin: 1vw;
          background: #f7fbfc;
          display: flex;
          flex-direction: row;
          justify-content: center;
          align-items: center;
          border-radius: 1vw;
        "
      />
      <div class="blance">
        <div class="blance1">
          Blance <br />
          -$18,750
        </div>
        <div class="blance2">
          Blance <br />
          $69,750
        </div>
      </div>
    </div>
    <div class="right">
      <span>% of Expenses Budget</span>
      <div class="budget">
        <h1>55%</h1>
      
      </div>
      <circle-progress
        id="circle2"
        :is-gradient="true"
        :gradient="{
          angle: 200,
          startColor: '#03fcb1',
          stopColor: '#00a6ff',
        }"
        style="
          width: 100px;
          padding: 2vw;
          margin: 1vw;
          background: #f7fbfc;
          display: flex;
          flex-direction: row;
          justify-content: center;
          align-items: center;
          border-radius: 1vw;
        "
      />
      <div class="blance">
        <div class="blance1">
          Blance <br />
          -$8,750
        </div>
        <div class="blance2">
          Blance <br />
          $78,750
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import "vue3-circle-progress/dist/circle-progress.css";
import CircleProgress from "vue3-circle-progress";
export default {
  components: { CircleProgress },
};
</script>

<style lang="scss" scoped>
main {
  margin: 2vw;
  width: 30vw;
  height: 30vw;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  justify-items: center;
  align-content: center;
  background: rgb(243, 243, 243);
  border-radius: 2vw;
}

.left,
.right {
  text-align: center;
  span {
    font-size: 1vw;
    font-weight: 700;
    color: rgba(0, 0, 0, 0.664);
  }
}

.blance {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  font-size: 0.7vw;
  font-weight: 700;
  color: rgba(0, 0, 0, 0.664);
}
.budget {
  position: relative;
  top: 0;
  left: 0;
}
.budget h1,
p {
  position: absolute;
  top: 5.2vw;
  left: 4vw;
  z-index: 1;
}
</style>
