<template>
  <div class="bg-white holder">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 col-md-3 order-1 order-md-2 imageContainer">
          <div class="mt-1 mb-1 my-0-md">
            <res-img image="checklist" :width="183" :height="150" />
          </div>
        </div>
        <div class="col-xs-12 offset-md-1 col-md-7 order-2 order-md-1">
          <h2>Start building a high quality audio or video dataset today</h2>
          <p>
            Whether you need a <strong>large scale video dataset</strong> or a
            <strong>large scale audio dataset</strong>, Twine is here to help.
          </p>
          <p>Contact us for a free quote.</p>
          <action-button label="Contact us" :url="Links.CONTACT_US" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ResImg from "@c/Common/ResImg.vue";
import ActionButton from "@c/Common/ActionButton.vue";

import Links from "@constants/Links.js";

export default {
  name: "StartBuilding",
  components: {
    ResImg,
    ActionButton,
  },
  data: function ActionButton() {
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
