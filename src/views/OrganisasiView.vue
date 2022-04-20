<script setup>
import { onMounted } from "vue";
import Navbar from "../components/navbar.vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundImage =
    "Url('src/assets/others.png')";
  document.getElementsByTagName("body")[0].style.backgroundSize = "cover";
});
</script>
<template>
  <navbar />
  <section id="familyyy">
    <div class="container">
      <div class="row text-center pt-4 pb-4">
        <div class="col text-white">
          <h2><b>GDSC Uin Suska</b></h2>
        </div>
      </div>
      <div class="row shuffle-wrapper">
        <div class="col-md-4 mb-3 shuffle-item">
          <div class="card">
            <div class="position-relative rounded hover-wrapper">
              <img
                src="../assets/gdsc1.jpg"
                class="img-fluid rounded w-100"
                alt=""
              />
              <div class="card-body">
                <div class="hover-overlay"></div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-4 mb-3 shuffle-item">
          <div class ="card">
            <div class="position-relative rounded hover-wrapper">
              <img
                src="../assets/gdsc3.jpg"
                class="img-fluid rounded w-100"
                alt=""
              />
              <div class="card-body">
                <p class="card-text">Meet Up w/ Core Team GDSC</p>
                <div class="hover-overlay">
                  <div class="hover-content"></div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-4 mb-3 shuffle-item">
          <div class="card">
            <div class="position-relative rounded hover-wrapper">
              <img
                src="../assets/gdsc2.jpg"
                class="img-fluid rounded w-100"
                alt=""
              />
              <div class="card-body">
                <div class="hover-overlay">
                  <div class="hover-content"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section id="familyy">
    <div class="container">
      <div class="row text-center pt-4 pb-4">
        <div class="col text-white">
          <h2><b>Predatech</b></h2>
        </div>
      </div>
      <div class="row shuffle-wrapper">
        <div class="col-md-4 mb-3 shuffle-item">
          <div class="card">
            <div class="position-relative rounded hover-wrapper">
              <img
                src="../assets/predatech1.jpg"
                class="img-fluid rounded w-100"
                alt=""
              />
              <div class="card-body">
                <div class="hover-overlay"></div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-4 mb-3 shuffle-item">
          <div class ="card">
            <div class="position-relative rounded hover-wrapper">
              <img
                src="../assets/predatech2.jpg"
                class="img-fluid rounded w-100"
                alt=""
              />
              <div class="card-body">
                <p class="card-text">Family Gathering Predatech</p>
                <div class="hover-overlay">
                  <div class="hover-content"></div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-4 mb-3 shuffle-item">
          <div class="card">
            <div class="position-relative rounded hover-wrapper">
              <img
                src="../assets/predatech3.jpg"
                class="img-fluid rounded w-100"
                alt=""
              />
              <div class="card-body">
                <div class="hover-overlay">
                  <div class="hover-content"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="family">
    <div class="container">
      <div class="row text-center pt-4 pb-4">
        <div class="col text-white">
          <h2><b>HIMATIF</b></h2>
        </div>
      </div>
      <div class="row shuffle-wrapper">
        <div class="col-md-4 mb-3 shuffle-item">
          <div class="card">
            <div class="position-relative rounded hover-wrapper">
              <img
                src="../assets/kongres1.jpg"
                class="img-fluid rounded w-100"
                alt=""
              />
              <div class="card-body">
                <div class="hover-overlay"></div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-4 mb-3 shuffle-item">
          <div class="card">
            <div class="position-relative rounded hover-wrapper">
              <img
                src="../assets/kongres2.jpg"
                class="img-fluid rounded w-100"
                alt=""
              />
              <div class="card-body">
                <p class="card-text">Kongres XV HIMATIF</p>
                <div class="hover-overlay">
                  <div class="hover-content"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-3 shuffle-item">
          <div class="card">
            <div class="position-relative rounded hover-wrapper">
              <img
                src="../assets/kongres3.jpg"
                class="img-fluid rounded w-100"
                alt=""
              />
              <div class="card-body">
                <div class="hover-overlay">
                  <div class="hover-content"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>




  <footer class="page-footer bg-gradient">
    <div class="container">
          <h7>
            © RAUDYAH MAGHFIRAH
          </h7>
        </div>
  </footer>
</template>

<style>
.hover-wrapper {
  overflow: hidden;
}
.hover-wrapper img {
  transition: 0.3s ease;
  transform: scale(1.1);
}
.hover-wrapper:hover img {
  transform: scale(1);
}
.hover-wrapper:hover .hover-overlay {
  opacity: 1;
  visibility: visible;
}

.hover-overlay {
  position: absolute;
  height: 100%;
  width: 100%;
  border-radius: inherit;
  top: 0;
  left: 0;
  background: rgba(0, 0, 0, 0.3);
  opacity: 0;
  visibility: hidden;
  transition: 0.3s ease;
}

.hover-content {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  left: 0;
  right: 0;
}
.container {
  margin-bottom: 20px;
  text-align: center;
}

.card-text{
  text-align: center;


}
</style>
