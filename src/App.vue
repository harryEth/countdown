<template>
  <div id="app">
    <img width="25%" src="./assets/bf-image-footer.png">
    <BfText msg="Date is coming!"/>
    <flip-countdown deadline="2020-12-08 20:00:00"></flip-countdown>
  </div>
</template>

<script>
import BfText from "./components/Text";
import FlipCountdown from "vue2-flip-countdown";

export default {
  name: "App",
  components: {
    BfText,
    FlipCountdown
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 200px;
}
body {
  background-color: black;
  background: url("https://i.ibb.co/bHHn9NT/fericier.png");
  background-repeat: no-repeat;
  background-size: cover;
  height: 74vh;
  width: auto;
  overflow-y: hidden;
}
</style>
