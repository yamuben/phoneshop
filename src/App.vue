<template>
  <div>
    <HomeScreen></HomeScreen>
  </div>
</template>

<script>
import HomeScreen from "./view/HomeScreen.vue";
export default {
  name: "App",
  components: {
    HomeScreen,
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>
