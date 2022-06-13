<template>
  <div class="header">
    <div class="search-bar">
      <button type="submit"><i class="fa fa-search"></i></button>
      <input type="search" placeholder="Search here..." />
    </div>
    <div class="right">
      <div class="notification"><i class="fa fa-bell"></i></div>
      <div class="messages"><i class="fa fa-comments"></i></div>
      <div class="profile"><img src="@/assets/person.png" alt="" /></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "header_",
};
</script>

<style lang="scss" scoped>
.header {
  
  padding: 2vw 0vw;
  background: rgb(240, 240, 240);
  width: 70vw;
  height: fit-content;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  .search-bar,
  .notification,
  .messages,
  .profile {
    
    padding: 1vw;
    img {
      width: 3vw;
      height: 3vw;
      border-radius: 50%;
    }
  }

  .search-bar {
    display: flex;
    // height: 2vw;
    background-color: #fff;
    margin: 0.2vw 0.1vw;
    border-radius: 5vw;
    margin-left: 5vw;

    input {
      background: none;
      width: 30vw;
      // height: 5vw;
      outline: none;
      border: none;
      border-radius: 20vw;
      display: flex;
      align-items: center;
      font-size: 1vw;
        margin-left: 1vw;
      :-ms-input-placeholder {
        border-radius: 20vw;
        background-color: none;
        
      }
    }
  }

  button {
    border: none;
    outline: none;
    background: none;
  }
  .right {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
  }
}
.fa{
  font-size: 1.2vw;
}
</style>
