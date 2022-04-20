<script setup>
import NavBar from "../components/NavBar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundImage = "url('src/assets/portofolio.png') ";
  document.getElementsByTagName("body")[0].style.backgroundSize = "cover";
});
</script>

<template>
  <NavBar />
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-sm-4">
        <div class="card">
          <img
            src="src/assets/portofolio1.png"
            class="card-img-top"
            height="415px"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Redesign Aplikasi LinkAja</h5>
            <p class="card-text">Saya pernah redesign aplikasi LinkAja menggunakan AdobeXD</p>
            <a target = "_blank" href="https://dribbble.com/shots/17847260-Redesign-App?added_first_shot=true" class="btn btn-outline-secondary ">Dribble</a>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="card">
          <img
            src="src/assets/portofolio2.png"
            class="card-img-top"
            height="415px"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Design Logo Go Green Office.Co</h5>
            <p class="card-text">Go Green Office.Co merupakan aplikasi yang mendukung gerakan peduli linkungan</p>
            <a target = "_blank" href="https://www.canva.com/design/DAE5_PNOHfs/kDx93qT1j5s82juOTwPOfw/edit#" class="btn btn-outline-secondary ">Canva</a>
          </div>
        </div>
      </div>
    </div>
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
.card-img-top {
  padding: 15px;
  background-color: #a99b8e ;
}
.card {
  margin-bottom: 70px;
}
.card-body {
  text-align: center;
  background-color: #a99b8e;
}
.card-title {
  font-size: 20px;
  color: #62360D;
}
.card-text {
  font-size: 15px;
  color: #ffffff;
}

</style>