<template>
  <div class="container-fluid px-0">
    <div class="video-wrapper">
      <video
        ref="videoRef"
        src="@/assets/images/body/video/laser.mp4"
        class="video-element"
        autoplay
        muted
        @ended="restartVideo"
      ></video>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from "vue";

const videoRef = ref(null);

const playVideo = () => {
  videoRef.value.play();
};

const restartVideo = () => {
  videoRef.value.currentTime = 0;
  videoRef.value.play();
};

onMounted(() => {
  videoRef.value.addEventListener("ended", restartVideo);
  playVideo();
});
</script>


<style scoped>
.video-wrapper {
  position: relative;
  width: 100%;
  height: auto;
  overflow: hidden;
  margin: 0;
  padding: 0;
  line-height: 0;
}

.video-element {
  width: 100%; 
  height: auto;
}

@media (max-width: 576px) {

  .video-wrapper {
    height: auto;
  }
}

@media (min-width: 577px) and (max-width: 991px) {
  
  .video-wrapper {
    height: auto; 
  }
}
</style>

