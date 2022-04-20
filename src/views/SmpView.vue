<script setup>
import NavBar from "../components/NavBar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundImage = "url('src/assets/others.png')";
  document.getElementsByTagName("body")[0].style.backgroundSize = "cover";
});
</script>

<template>
  <NavBar />
  <div class="burger">
    <div class="line1"></div>
    <div class="line2"></div>
    <div class="line3"></div>
  </div>

  <h1>SMP</h1>

  <div class="gallery">
    <a href="src/assets/smp1.jpg" data-lightbox="mygallery"><img src="src/assets/smp1.jpg"></a>
    <a href="src/assets/smp2.jpg" data-lightbox="mygallery"><img src="src/assets/smp2.jpg"></a>
    <a href="src/assets/smp3.jpg" data-lightbox="mygallery"><img src="src/assets/smp3.jpg"></a>
    <a href="src/assets/smp4.jpg" data-lightbox="mygallery"><img src="src/assets/smp4.jpg"></a>
    <a href="src/assets/smp5.jpeg" data-lightbox="mygallery"><img src="src/assets/smp5.jpeg"></a>

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
body {
  font-family: sans-serif;
}

h1 {
  text-align: center;
  color: #5d3232;
  margin: 30px 0 50px;
}

.gallery {
  margin: 50px 50px;
  border: 3px solid wheat;
  scale: 30%;
}


.gallery img {
  margin-left: 60px;
  width: 15%;
  padding: 10px;
  filter: grayscale(100%);
  transition: 1s;
  position: relative;
}

.gallery img:hover {
  filter: grayscale(0);
  transform: scale(1.1);
}

.container {
  margin-top: 220px;
  text-align: center;
}
</style>
