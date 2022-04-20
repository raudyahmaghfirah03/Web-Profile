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
  <div class="accordion accordion-flush" id="accordionFlushExample">
    <div class="accordion-item">
      <h2 class="accordion-header" id="flush-headingOne">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
          Biodata
        </button>
      </h2>
      <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
        <div class="accordion-body"> Nama saya Raudyah Maghfirah. Saya lahir pada tanggal 03 September 2001. Saya Berasal dari salah satu Beautiful Village di Indonesia,  yaitu Batusangkar. Saya dilahirkan sebagai anak bungsu yang memiliki 3 saudara perempuan.
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header" id="flush-headingTwo">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
          Riwayat Pendidikan
        </button>
      </h2>
      <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
        <div class="accordion-body">
          <ul>
            <li>TK : TK Pembina Pagaruyung (2007-2008) </li>
            <li>SD : SDN 28 Bukit Gombak (2008-2014)</li>
            <li>SMP : MTsN Batusangkar (2014-2017)</li>
            <li> SMA : MAN 2 Tanah Datar (2017-2020)</li>
          </ul>
          </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header" id="flush-headingThree">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
          Organisasi
        </button>
      </h2>
      <div id="flush-collapseThree" class="accordion-collapse collapse" aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
        <div class="accordion-body">
          <ul>
            <li>Core Team GDSC UIN Sultan Syarif Kasim Riau Divisi Partnerships and Programs</li>
            <li>Anggota Predatech Divisi Data Center and Start-Up</li>
            <li>Pengurus Inti House Of Microsoft lab UIN Sultan Syarif Kasim Riau</li>
            <li>Anggota Himpunan Mahasiswa Teknik Informatika (HIMATIF) Divisi Forensik</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

</template>

<style scoped>

.accordion {
  margin-left: 400px;
  margin-top: 65px;
  margin-right: 50px;
}




</style>
