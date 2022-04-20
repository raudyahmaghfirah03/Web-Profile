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

  <h1>Kuliah</h1>

  <div class="gallery">
    <a href="src/assets/kuliah1.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah1.jpg"></a>
    <a href="src/assets/kuliah2.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah2.jpg"></a>
    <a href="src/assets/kuliah3.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah3.jpg"></a>
    <a href="src/assets/kuliah4.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah4.jpg"></a>
    <a href="src/assets/kuliah5.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah5.jpg"></a>
    <a href="src/assets/kuliah6.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah6.jpg"></a>
    <a href="src/assets/kuliah7.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah7.jpg"></a>
    <a href="src/assets/kuliah8.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah8.jpg"></a>
    <a href="src/assets/kuliah9.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah9.jpg"></a>
    <a href="src/assets/kuliah10.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah10.jpg"></a>
    <a href="src/assets/kuliah11.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah11.jpg"></a>
    <a href="src/assets/kuliah12.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah12.jpg"></a>
    <a href="src/assets/kuliah13.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah13.jpg"></a>
    <a href="src/assets/kuliah14.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah14.jpg"></a>
    <a href="src/assets/kuliah15.jpg" data-lightbox="mygallery"><img src="src/assets/kuliah15.jpg"></a>
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
