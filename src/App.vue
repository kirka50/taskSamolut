<template>
  <div class="main">
    <header>
      <Navbar/>
    </header>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: #F4F6FB;
  height: 100vh;
  width: 100%;
}
.main {
}
</style>
<script>
import Navbar from "@/components/Navbar";
export default {
  components: {Navbar}
}
</script>