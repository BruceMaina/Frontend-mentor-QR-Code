<template>
  <div id="app_vue">
     <div class="QRCODE">
        <div class="insideqr">
          <img src="../src/assets/image-qr-code.png" alt="" style="border-radius:15px;">
        </div>
        <div>
        <div class="header">
          <p1>Improve your front-end <br> skills by building projects</p1>
        </div>
          <div class="header2">
            <p2>Scan the QR code to visit Frontend <br> Mentor and take your coding skills to <br> the next level</p2>
          </div>
        </div>
        </div>
     </div>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
@font-face {
  font-family: "Outfit";
  src: local("Outfit"),
   url("../src/fonts/Outfit/Outfit-VariableFont_wght.ttf") format("truetype");
}
#app {
  font-family: Outfit;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: hsl(212, 45%, 89%);
  text-align: center;
  width: 100vw;
  height: 100vh;
  color: #2c3e50;
  padding-top: 10px;
}
.QRCODE {
  background-color: hsl(0, 0%, 100%);
  height: 62vh;
  width: 20vw;
  margin-left: 38%;
  margin-top: 10%;
  box-shadow: rgba(0, 0, 0, 0.30) 0px 3px 8px;
  border-radius: 35px;
  overflow: hidden;
  position: relative;
}
.insideqr {
  /* overflow: hidden; */
  display: flex;
  /* flex-direction: inherit; */
  /* align-items: center; */
  /* justify-content: center; */
  width: 300px;
  height: 300px;
  margin-left: 3%;
  margin-top: 4%;
  border-radius: 40px;
  position: relative;
  /* padding: 20px; */
}
.header {
  font-weight: 800;
  display: flex;
  font-size: 130%;
  padding-top: 25px;
  padding-bottom: 10px;
  padding-left: 50px;
  text-align-last: justify;
  /* justify-content: left; */
  /* flex-direction: row-reverse; */
}
.header2 {
  font-size: 80%;
  justify-content: flex-start;
  /* text-align-last: justify; */
}
</style>
