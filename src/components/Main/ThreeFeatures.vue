<template>
  <div class="bg-white holder">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 col-md-4">
          <p class="lead fw-bold">High quality &amp; vetted freelancers</p>
          <p>
            Twine is a quality-focused freelance marketplace and every
            <strong>freelance actor</strong> or <strong>presenter</strong> who
            contributes to your dataset will be individually vetted by Twine.
          </p>
        </div>
        <div class="col-xs-12 col-md-4">
          <p class="lead fw-bold">Fast &amp; scalable data collection</p>
          <p>
            Your dedicated account manager will work to your project timelines,
            helping you to scale the <strong>data collection</strong> at the
            speed and scale you need.
          </p>
        </div>
        <div class="col-xs-12 col-md-4">
          <p class="lead fw-bold">Large-scale &amp; diverse datasets</p>
          <p>
            Twine’s freelance community is spread across 190+ countries, so if
            you need actors from a specific demographic, then we’ve got you
            covered.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Links from "@constants/Links.js";

export default {
  components: {},
  name: "ThreeFeatures",
  data: function() {
    return {
      Links,
    };
  },
};
</script>

<style lang="scss" scoped>
.holder {
  padding: 50px 0;
}
</style>
