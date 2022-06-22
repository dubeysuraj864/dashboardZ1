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
          <li>
          
              <input type="checkbox" id="dashboard-btn" />
              <i class="fa fa-home"></i>
            <label for="dashboard-btn">Dashboard    <i
              class="fa fa-angle-down" id="arrow"
            ></i></label>
         
            <ul class="dropdown-dashboard">
              <li>Create</li>
            </ul>
          </li>
          <li>
            <i class="fa fa-book"></i>Pages
            
          </li>
          <li>
            <i class="fa fa-windows"></i>Applications
          </li>
          <li>
            <i class="fa fa-pagelines"></i> UI Components
          </li>
          <li>
            
          </li>
          <li>
            <i class="fa fa-address-card"></i>Forms
          </li>
          <li>
            <i class="fa fa-bar-chart"></i>Charts
          </li>
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
  width: 20vw;
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
.navlinks{
  margin: 3vw 0vw;
  ul li {
    margin: 3vw 1vw;
    font-weight: 700;
    font-size: 1vw;
    color: rgb(67, 56, 112);
    list-style: none;
  }
  i {
    margin-right: 2vw;
  }
  .fa {
    font-size: 1.2vw;
  }
}
label{
  font-family:Arial, Helvetica, sans-serif;
  font-weight: 700;
    font-size: 1vw;
    color: rgb(67, 56, 112);
    list-style: none;
}

input{
  display: none;
}

.fa-angle-down {
  font-size: 2vw;
  font-weight: 700;
  margin-left: 2vw;
}

.dropdown-dashboard {
  display: none;
}
#dashboard-btn:checked ~ .dropdown-dashboard {
  display: block;
   
}
#dashboard-btn:checked ~ .fa-angle-down{

    transform: rotate(180deg);

}
</style>
