<template>
  <div class="wrapper-small md:px-10">
    <div class="header mt-5">
      <Hero />
      <Social />
    </div>

    <div class="pt-64">
      <div
        class="flex justify-center items-center text-base font-semibold text-gray-600"
      >
        <h4 class="text-center">Recent Work</h4>
        <i class="bx bx-chevrons-down ml-1 mt-1"></i>
      </div>

      <div>
        <Projects />
      </div>
    </div>
  </div>
</template>

<script>
import Hero from "../components/Hero.vue";
import Social from "../components/Social.vue";
import Projects from "../components/Projects.vue";
import GoodThings from "../components/GoodThings.vue";

export default {
  components: {
    Hero,
    Social,
    Projects,
    GoodThings
  },
  head() {
    return {
      script: [
        { src: "https://identity.netlify.com/v1/netlify-identity-widget.js" }
      ]
    };
  }
};
</script>

<style></style>
