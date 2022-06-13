<template>
  <div>
    <nav>
      <div class="logo">
        <img class="logo-image" src="../assets/logo.png" alt="" /><span
          class="logo-text"
          >Finance</span
        >
      </div>
      <div class="navlinks">
        
        <ul>
          
          <li><i class="fa fa-home"></i>Dashboard<i class="fa fa-angle-down"></i>
          <ul class="dropdown">
            <li>Create</li>

          </ul>
          </li>
          <li><i class="fa fa-book"></i>Pages<i class="fa fa-angle-down"></i> </li>
          <li><i class="fa fa-windows"></i>Applications<i class="fa fa-angle-down"></i></li>
          <li><i class="fa fa-pagelines"></i> UI Components<i class="fa fa-angle-down"></i></li>
          <li><i class="fa fa-trello"></i> Widgets<i class="fa fa-angle-down"></i></li>
          <li><i class="fa fa-address-card"></i>Forms<i class="fa fa-angle-down"></i></li>
          <li><i class="fa fa-bar-chart"></i>Charts<i class="fa fa-angle-down"></i></li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Nav-bar",
};
</script>

<style lang="scss" scoped>
nav {
   width:20vw;
  height: fit-content;
  height: 100vh;
  background: rgb(240, 240, 240);
  padding: 1vw;
}
.logo {
  background-color: #fff;
  border-radius: 1vw;
  padding: 1vw;
  margin: 1vw;
  display: flex;
  justify-content: center;
  align-items: center;
  .logo-image {
    width: 3vw;
    height: 3vw;
    border-radius: 50%;
  }
  .logo-text {
    margin: 1vw;
    font-weight: 700;
    font-size: 2vw;
    color: rgb(93, 74, 167);
  }
}
.navlinks {
  margin: 3vw 0vw;
  ul li {
    margin: 3vw 1vw;
    font-weight: 700;
    font-size: 1vw;
    color: rgb(67, 56, 112);
    list-style: none;
  }
  i{
    margin-right: 2vw;
  }
  .fa{
  font-size: 1.2vw;
}

}

  .fa-angle-down{
    font-size: 2vw;
    font-weight: 700;
    margin-left: 2vw;
  }
</style>
