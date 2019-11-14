<template>
  <div class="home">
    <VideoPlayer msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import VideoPlayer from "@/components/VideoPlayer.vue";

export default {
  name: "home",
  components: {
    VideoPlayer
  }
};
</script>
