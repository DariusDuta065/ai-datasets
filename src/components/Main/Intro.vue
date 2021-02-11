<template>
  <div class="container holder">
    <div class="row">
      <div class="col-xs-12 col-md-8 order-2 order-md-1">
        <h1>Build quality datasets for AI</h1>
        <p class="lead">Video collection for machine learning</p>
        <p>
          Access Twine’s global community of 400,000+ freelancers and build high
          quality <strong>audio datasets</strong> and <strong>video datasets</strong> customised to
          your requirements.
        </p>
        <p>
          Get next level service with Twine Enterprise, which gives you access
          to:
        </p>
        <ul>
          <li>A dedicated account manager</li>
          <li>
            All payouts to <strong>data collectors</strong> managed securely through Twine
          </li>
          <li>
            Fully customizable <strong>participant onboarding process</strong> built to
            your specifications
          </li>
          <li>
            The size of each dataset and speed of <strong>data collection</strong> are
            customized to your requirements
          </li>
        </ul>
        <action-button label="Contact us" :url="Links.CONTACT_US" />
      </div>
      <div class="col-xs-12 col-md-4 order-1 order-md-2 imageContainer">
        <div class="mt-1 mb-1 my-0-md">
          <res-img image="creative-and-buyer" :width="214" :height="119" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ActionButton from "@c/Common/ActionButton.vue";
import ResImg from "@c/Common/ResImg.vue";

import Links from "@constants/Links.js";

export default {
  components: {
    ActionButton,
    ResImg,
  },
  name: "Intro",
  data: function() {
    return {
      Links,
    };
  },
};
</script>

<style lang="scss" scoped>
.holder {
  margin: 30px auto;
}

.imageContainer {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
