<template>
  <img class="girlImg" alt="Vue logo" src="./assets/coffeegirl.png">
  <HelloWorld msg="coffee"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.girlImg{
  width:80%;
  height:auto;}


@media screen and (max-width: 481px) {

.girlImg{
  width:100%;
  height:auto;}
}

</style>
