<template>
  <intro />
  <three-features />
  <how-it-works />
  <getting-started />
  <video-vs-audio />
  <start-building />
</template>

<script>
import Intro from "@c/Main/Intro";
import ThreeFeatures from "@c/Main/ThreeFeatures";
import HowItWorks from "@c/Main/HowItWorks";
import GettingStarted from "@c/Main/GettingStarted";
import VideoVsAudio from "@c/Main/VideoVsAudio";
import StartBuilding from "@c/Main/StartBuilding";

export default {
  components: {
    Intro,
    ThreeFeatures,
    HowItWorks,
    GettingStarted,
    VideoVsAudio,
    StartBuilding,
  },
  name: "Main",
};
</script>
