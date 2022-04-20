<script setup>
import NavBar from "../components/NavBar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName(
    "body"
  )[0].style.backgroundImage = `url('src/assets/others.png')`;
  document.getElementsByTagName("body")[0].style.backgroundSize = `cover`;
});
</script>

<template>
  <NavBar />
  <div class="card mb-3">
    <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/zSWdZVtXT7E">" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay;
            clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <div class="card-body">
      <h5 class="card-title">Interstellar</h5>
      <p class="card-text">"Earth's future has been riddled by disasters, famines, and droughts. There is only one way to ensure mankind's survival: Interstellar travel.
        A newly discovered wormhole in the far reaches of our solar system allows a team of astronauts to go where no man has gone before, a planet that may have the right environment to sustain human life."</p>
    </div>
  </div>
  <div class="card">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/ej3ioOneTy8" title="YouTube video player"
            frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope;
            picture-in-picture" allowfullscreen></iframe>
    <div class="card-body">
      <h5 class="card-title">The Martians</h5>
      <p class="card-text">"During a manned mission to Mars, Astronaut Mark Watney is presumed dead after a fierce storm and left behind by his crew.
        But Watney has survived and finds himself stranded and alone on the hostile planet. With only meager supplies, he must draw upon his ingenuity,
        wit and spirit to subsist and find a way to signal to Earth that he is alive. Millions of miles away, NASA and a team of international scientists work tirelessly to bring "the Martian" home, while his crewmates concurrently plot a daring, if not impossible, rescue mission. As these stories of incredible bravery unfold, the world comes together to root for Watney's safe return."</p>
    </div>
  </div>
  <div class="card">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/H1WYnJF1Pwo" title="YouTube video player"
            frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope;
            picture-in-picture" allowfullscreen></iframe>
    <div class="card-body">
      <h5 class="card-title">Space Sweepers</h5>
      <p class="card-text">"In the year 2092, space is full of dangerous floating garbage like discarded satellites and deserted spaceships. The crew of The Victory travels through space looking for the garbage they can make money off, while also competing with junk collector ships from other countries and using the speediness of their craft to defeat their rivals."</p>
    </div>
  </div>
</template>

<style>

.card {
  margin-left: 385px;
  margin-top: 20px;
  width: 560px;
}
.card-body {
  width: 560px;
  text-align: center;
  background-color: #a6a9a8;
}
.card-title {
  font-family: "Open Sans";
  font-size: 20px;
  color: #000000;
}
.card-text {
  font-family: "Open Sans";
  font-size: 15px;
  color: #0a4657;
}
</style>