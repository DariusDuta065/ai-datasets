<template>
  <div class="bg-white holder">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 col-md-6 order-1 order-md-1 imageContainer">
          <div class="mt-1 mb-1 my-0-md">
            <res-img image="creative-equipment" :width="287" :height="200" />
          </div>
        </div>
        <div class="col-xs-12 col-md-6 order-2 order-md-2">
          <h2>How do I get started?</h2>
          <p>
            Most AI dataset resourcing companies offer standardized packages,
            with no personalized service or support during the project
            implementation.
          </p>
          <p>
            Twine’s Enterprise system is fully flexible and designed to satisfy
            the requirements of your projects.
          </p>
          <p>
            Contact us to get a <strong>free estimate</strong> for your project.
          </p>
          <div class="d-flex">
            <action-button label="Contact us" :url="Links.CONTACT_US" />
          </div>
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
  name: "GettingStarted",
  data: function() {
    return {
      Links,
      publicPath: process.env.BASE_URL,
    };
  },
};
</script>

<style lang="scss" scoped>
.holder {
  padding: 50px 0;
}
.imageContainer {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
