<template>
  <div class="header_body">
    <div class="header_content">
      <div class="first_half">
        <div class="logo">САМОЛЁТ SCUM</div>
        <div class="nav_buttons">
          <button>Инструкция</button>
          <button>О нас</button>
          <button>Услуги</button>
        </div>
      </div>

      <div class="login_panel">
        <button class="login_but">Войти <img :src="mySVG" alt=""/></button>
      </div>
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
  padding: 1% 1% 1.5% 1%;
}

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
  line-height: 39px;
  color: #007BFB;
  margin-right: 10%;
  white-space: nowrap;
}

.login_panel {
  display: flex;
  flex-direction: row;



}

.nav_buttons {

  display: flex;
  flex-direction: row;
  justify-content: flex-start;


}
.nav_buttons button {
  margin-left: 10%;
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
  flex-direction: row;
}
</style>