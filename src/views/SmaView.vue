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

  <h1>SFMA</h1>

  <div class="gallery">
    <a href="src/assets/sma1.jpg" data-lightbox="mygallery"><img src="src/assets/sma1.jpg"></a>
    <a href="src/assets/sma2.jpg" data-lightbox="mygallery"><img src="src/assets/sma2.jpg"></a>
    <a href="src/assets/sma3.jpg" data-lightbox="mygallery"><img src="src/assets/sma3.jpg"></a>
    <a href="src/assets/sma4.JPG" data-lightbox="mygallery"><img src="src/assets/sma4.JPG"></a>
    <a href="src/assets/sma5.JPG" data-lightbox="mygallery"><img src="src/assets/sma5.JPG"></a>
    <a href="src/assets/sma6.jpg" data-lightbox="mygallery"><img src="src/assets/sma6.jpg"></a>
    <a href="src/assets/sma7.jpg" data-lightbox="mygallery"><img src="src/assets/sma7.jpg"></a>
    <a href="src/assets/sma8.jpg" data-lightbox="mygallery"><img src="src/assets/sma8.jpg"></a>
    <a href="src/assets/sma9.jpg" data-lightbox="mygallery"><img src="src/assets/sma9.jpg"></a>
    <a href="src/assets/sma10.jpg" data-lightbox="mygallery"><img src="src/assets/sma10.jpg"></a>
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
  color: #532727;
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
  margin-top: 50px;
  text-align: center;
}

</style>
