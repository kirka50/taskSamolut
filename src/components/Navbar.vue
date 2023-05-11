<template>
  <div class="header_body">
    <div style="display: flex">
      <a class="logo">Самолёт</a>
      <div class="nav_buttons">
        <button>Инструкция</button>
        <button>О нас</button>
        <button>Главная</button>
      </div>
    </div>
    <button class="login_button">Войти</button>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {
      mySVG: require('@/assets/login-svgrepo-com1.png')
    }
  }

}

</script>

<style scoped>

.header_body {
  background-color: #FFFFFF;
  border-radius: 0 0 50px 50px;
  padding: 1% 1% 1% 1%;
  display: flex;
  justify-content: space-between;
}
.logo{
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 32px;
  color: #007BFB;
  margin-right: 10%;
  white-space: nowrap;
}
.nav_buttons{
  white-space: nowrap;
}
.nav_buttons button {
  background: none;
  border: none;
  margin-left: 10%;
}
.login_button{
  white-space: nowrap;
  background: #007BFB;
  border-radius: 50px;
  border: none;
  font-family: 'Montserrat', sans-serif;
  font-weight: 400;
  font-size: 24px;
  line-height: 29px;
  color: #FFFFFF;
  display: flex;
  padding: 1%;
  flex-wrap: nowrap;
}
/*
.header_content {
  display: flex;
  flex-direction: row;
  justify-content: space-between;


}
.first_half{
  display: flex;
  flex-direction: row;
  justify-content: space-between;

}

.logo {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 32px;
  color: #007BFB;
  margin-right: 10%;
  white-space: nowrap;

}

.login_panel {
  display: flex;
  flex-direction: row;
  margin-right: 1%;



}

.nav_buttons {

  display: flex;
  flex-direction: row;
  justify-content: flex-start;



}

.nav_buttons button {
  margin-left: 10%;
  border: none;
  background: none;
  white-space: nowrap;
}
.login_but {
  background: #007BFB;
  border-radius: 50px;
  border: none;
  font-family: 'Montserrat', sans-serif;
  font-weight: 400;
  font-size: 24px;
  line-height: 29px;
  color: #FFFFFF;
  display: flex;
  padding: 10%;
  flex-wrap: nowrap;
}*/
</style>