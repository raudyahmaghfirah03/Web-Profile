<script setup>
import NavBar from "../components/NavBar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundImage =
    "url('src/assets/others.png')";
  document.getElementsByTagName("body")[0].style.backgroundSize = "cover";
});
</script>

<template>
  <NavBar />
  <table class="table table-striped">
    <thead>
      <tr>
        <th scope="col">No</th>
        <th scope="col">Title</th>
        <th scope="col">Singer</th>
        <th scope="col">Link Spotify</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">1</th>
        <td>Meant 2 Be</td>
        <td>Shakira Jasmine ft. Nuca</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/35xF6iKiyjohKJgg7dntw4?si=771f1f58b7e94349">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td>Ghost</td>
        <td>Justin Bieber</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/6I3mqTwhRpn34SLVafSH7G?si=124c3562d7ae4ff6">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Stuck In The Moment</td>
        <td>Justin Bieber</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/1DyV9obL0pPibOjW5ufg15?si=1e49a72034694acc">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td>Senyum</td>
        <td>As'ad Motawh</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/2AYjPlGkQx6NDxdx7csmIT?si=2d0a7094a5594ced">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td>Lebih Baik</td>
        <td>CJR</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/1Ky2q4CqKqPyawYwkq1IDk?si=fd9aa0a7fe564868">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td>That Should Be Me</td>
        <td>Justin Bieber</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/0aPZbnkMoWJaJ5CNVLCj8S?si=11003934b3ff4cd1">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td>True Colors</td>
        <td>Anna Kendrik ft. Justin Timberlake</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/2ORrgw8M0ZbrFlm5cpaKCv?si=c720c5233b924e4b">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td>Overboard</td>
        <td>Justin Bieber</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/1tzkJMX3gNjnpcHdLD0pM3?si=104f5aa776894e84">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">9</th>
        <td>The Joker and The Queen</td>
        <td>Ed Sheeren ft. Taylor Swift</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/6N1K5OVVCopBjGViHs2IvP?si=a8dcab6030d04102">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">10</th>
        <td>Wishes</td>
        <td>Jamie Miller</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/1kSBUhFBZT6z62eTTjeJLi?si=0fec8222e1b44089">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">11</th>
        <td>Stand By Me</td>
        <td>Boyce Avenue</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/068qo0w1Ki0cjnFYOUhAm2?si=91b88553882a4fe3">Click Here</a></td>
      </tr>
      <tr>
        <th scope="row">12</th>
        <td>Love Yourself</td>
        <td>Justin Bieber</td>
        <td><a class="music" target="_blank" href="https://open.spotify.com/track/1f8zcJPvJKvxAOjEqM0pyc?si=b6cf63a5a220407d">Click Here</a></td>
      </tr>
    </tbody>
  </table>
</template>
<style>
.table-striped {
  margin-top: 100px;
  margin-right: 50px;
  margin-left: 50px;
}
.music {
  color: #5d3232;
}
.table {
  margin-right: 200px;
  margin-left: 100px;
}
</style>
