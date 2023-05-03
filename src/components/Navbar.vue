<template>
  <div class="header_body">
    <div class="header_content">
      <div class="logo">САМОЛЁТ SCUM</div>
      <div class="nav_buttons">Кнопки</div>
      <div class="login_panel"><button class="login_but">Войти <img :src="mySVG" alt=""/></button></div>
    </div>
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
}

.header_content {
  display: flex;
  flex-direction: row;
  margin-left: 1%;
  margin-right: 1%;
  justify-content: space-between;


}

.logo {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 32px;
  line-height: 39px;
  color: #007BFB;
}
.login_panel{
  display: flex;
  flex-direction: row;

}
.nav_buttons{
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.login_but{
  background: #007BFB;
  border-radius: 50px;
  border: none;
  font-family: 'Montserrat', sans-serif;
  font-weight: 400;
  font-size: 24px;
  line-height: 29px;
  color: #FFFFFF;
  display: flex;
  padding: 5%;

}
</style>