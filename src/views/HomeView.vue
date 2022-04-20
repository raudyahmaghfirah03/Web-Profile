<script setup>
import NavBar from "../components/NavBar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundImage = "url('src/assets/homee.png')";
  document.getElementsByTagName("body")[0].style.backgroundSize = "cover";
});
</script>

<template>
  <NavBar />
  <div class="y" >

    <h1 class="h1">----- Hello -----</h1>
    <h2 class="h2">Welcome To</h2>
    <h3 class="h3">My Website</h3>
  </div>
</template>

<style scoped>
.y {
  margin-left: 270px;
  margin-top: 30px;
}
.h1 {
  font-family: "Open Sans";
  font-size: 50px;
  color: #62360D;
}
.h2 {
  font-family: "Open Sans";
  font-size: 70px;
  color: #62360D;
}

.h3 {
  font-family: "Open Sans";
  font-size: 70px;
  color: #62360D;
}

</style>
