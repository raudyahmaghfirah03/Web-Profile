<script>
export default {
  name: "NavBar",
};
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-transparent justify-content-center">
    <router-link class="y nav-link" to="/">HOME</router-link>
    <router-link class="y nav-link" to="/about">ABOUT</router-link>
    <router-link class="y nav-link" to="/portofolio">PORTOFOLIO</router-link>
    <router-link class="y nav-link" to="/mystore">MY STORE</router-link>
    <router-link class="y nav-link" to="/contact">CONTACT</router-link>
    <div class="y nav-link dropend">
      <a class=" x nav-link dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
        PHOTO
      </a>
      <ul class="dropdown-menu">
        <router-link class="x nav-link" to="/smp">SMP</router-link>
        <router-link class="x nav-link" to="/sma">SMA</router-link>
        <router-link class="x nav-link" to="/kuliah">KULIAH</router-link>
        <router-link class="x nav-link" to="/organisasi">ORGANISASI</router-link>
      </ul>
    </div>
    <div class="y nav-link dropend">
      <a class=" x nav-link dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
        OTHERS
      </a>
      <ul class="dropdown-menu">
        <router-link class="x nav-link" to="/family">FAMILY</router-link>
        <router-link class="x nav-link" to="/music">MUSIC</router-link>
        <router-link class="x nav-link" to="/book">BOOK</router-link>
        <router-link class="x nav-link" to="/film">FILM</router-link>
        <router-link class="x nav-link" to="/food">FOOD</router-link>
      </ul>
    </div>

  </nav>
</template>

<style scoped>

.x {
  color:#62360D;
}
.y{
  display: inline-block;
  margin-block: 2px;
  text-decoration: none;
  color: #5d3232;
  position: relative;
}
.y::after{
  content: '';
  width: 100%;
  height: 2px;
  background-color: #a99b8e;
  border-radius: 4px;
  position: absolute;
  left: 0;
  bottom: 0;
  transform: scaleX(0);
  transform-origin: left;
  transition: transform .25s ease;
}
.y:hover::after{
  transform: scaleX(1);
}

</style>
