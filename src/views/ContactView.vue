<script setup>
import NavBar from "../components/NavBar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundImage = "url('src/assets/contact.png')";
  document.getElementsByTagName("body")[0].style.backgroundSize = "cover";
});
</script>

<template>
  <NavBar />
  <div class="text-center gg">
    <a href="https://github.com/raudyahmaghfirah03">
      <i class="fa-brands fa-github y"></i>
    </a>
    <a target="_blank" href="https://www.facebook.com/raudyah.maghfirah.7">
      <i class="fa-brands fa-facebook y"></i>
    </a>
    <a href="https://www.instagram.com/raudyahmaghfirah">
      <i class="fa-brands fa-instagram y"></i>
    </a>
    <a href="tel:+6282285384671">
      <i class="fa-solid fa-phone y"></i>
    </a>
    <a href="https://www.youtube.com/channel/UC5rvRRliKnS_9VARx33e-rQ">
      <i class="fa-brands fa-youtube y "></i>
    </a>
  </div>
  <footer class="page-footer bg-gradient">
    <div class="container">
      <h7>
        © RAUDYAH MAGHFIRAH
      </h7>
    </div>
  </footer>
</template>

<style scoped>
.y {
  height: 50px;
  display: inline-block;
  animation: float 5s ease-in-out infinite;
  margin-left: 50px;
  margin-right: 50px;
  color: #451e20;
}
.fa-facebook{
  animation-delay: 1s;
}
.fa-instagram{
  animation-delay: 2s;
}
.fa-phone{
  animation-delay: 3s;
}
.fa-youtube{
  animation-delay: 4s;
}
.gg {
  margin-top: 250px;
}
.container {
  margin-top: 320px;
  text-align: center;
}
@keyframes float {
  0%{
    transform: translateY(0);
  }
  50%{
    transform: translateY(-15px);
  }
  100%{
    transform: translateY(0);
  }

}
</style>
