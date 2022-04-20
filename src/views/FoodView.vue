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
  <div class="card middle">
    <div class="top-section">
      <h3 class="h3"><b>PIZZA</b></h3>
      <img src="src/assets/pizza.jpg" alt="" >
    </div>

    <div class="info-section">
      <p>
        Pizza, dish of Italian origin consisting of a flattened disk of bread dough topped with some combination of olive oil,
        tomato, olives, mozzarella or other cheese, and many other ingredients, baked quickly usually,
        in a commercial setting, using a wood fired oven heated to a very high temperature and served hot. You can order in their Social Media.
      </p>
      <div class="social-button">
        <a href="https://www.facebook.com/pizzahutindonesiaofficial" target="_blank" title="Facebook"><i class="fab fa-facebook-f"></i></a>
        <a href="https://twitter.com/Pizza_HutID" target="_blank" title="Twitter"><i class="fab fa-twitter"></i></a>
        <a href="https://www.instagram.com/pizzahut.indonesia" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
  </div>
  <!--Scroll Top-->
  <button id="topBtn"><i class="fas fa-arrow-up"></i></button>
</template>

<style scoped>

.social-button a{
  float: bottom;
  margin-left: 55px;
  margin-top: 10px;
  display: inline-flex;
  text-decoration: none;
  font-size: 16px;
  width: 35px;
  height: 35px;
  color: #bbaea2;
  justify-content: center;
  align-items: center;
  position: relative;
}

.social-button a::before{
  content: "";
  position: absolute;
  width: 35px;
  height: 35px;
  background: linear-gradient(45deg, rgb(128, 12, 12), rgb(201, 19, 19));
  border-radius: 50%;
  z-index: -1;
  transition: 0.3s ease-in;
}

.social-button a:hover::before{
  transform: scale(0);
}
.social-buttona a i{
  transition: 0.3s ease-in;
}
.social-button a:hover i{
  background: linear-gradient(45deg, rgb(128, 12, 12), rgb(201, 19, 19));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  transform: scale(2.2);
}

.card{
  width: 400px;
  background: #f1f1f1;
  overflow: hidden;
  position: absolute;
  font-family: "montserrat",sans-serif;
  box-shadow: 0 0 20px #00000070;
}
.middle{
  position: absolute;
  top: 50%;
  left: 40%;
  transform: translate(-50%, -40%);
}
.top-section{
  position: relative;
}
.top-section img{
  width: 270px;
  margin-left: 65px;
  margin-top: 20px;
}

.info-section{
  padding: 40px;
  padding-top: 0;
  margin-bottom: 10px;
  color: #333;
}

p{
  margin-top: 10px;
  text-align: justify;
  font-size: 14px;
  line-height: 20px;
}

h3{
  margin-top: 15px;
  text-align: center;
  font-size: 20px;
  line-height: 20px;
}

#topBtn{
  position: fixed;
  bottom: 40px;
  right: 40px;
  font-size: 22px;
  width: 50px;
  height: 50px;
  background: #ff3300;
  color: #bbaea2;
  border: none;
  cursor: pointer;
  display: none;
}



</style>
