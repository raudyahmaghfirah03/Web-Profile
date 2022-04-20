<script setup>
import NavBar from "../components/NavBar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundImage = "url('src/assets/about.png')";
  document.getElementsByTagName("body")[0].style.backgroundSize = "cover";
});
</script>

<template>
  <NavBar />
  <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <div class="a">
        <router-link class="y nav-link" to="/catalog"
        ><button type="button" class="btn btn-outline-secondary">
          The Catalogue
        </button></router-link
        >
      </div>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="src/assets/store1.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Home Furniture</h5>
          <p>Furniture Decoration</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="src/assets/store2.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Minimalist Decoration</h5>
          <p>You can se the catalogue for you reference</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="src/assets/store3.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Modern Decoration</h5>
          <p>You can se the catalogue for you reference</p>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>

</template>

<style scoped>
.carousel-inner {
  padding: 50px;
}
img {
  max-width: 100%;
}

.a {
  font-family: "Joyce";
  padding: 30px;
  margin-top: -900px;
}
@media screen and (max-width: 360px) {
  body {
  }
}
</style>
