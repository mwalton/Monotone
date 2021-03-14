<template>
  <div class="wrapper mx-auto px-10">
    <hr class="h-px mt-6 border-gray-300 max-w-screen-xl mx-auto" />
    <div class="md:py-10">
      <div>
        <Social />
      </div>
      <nuxt-link class="nav-link hover:text-primary" to="credits"
        >Credits</nuxt-link
      >
      <div>
        <img
          src="~/assets/nothing_unusual.svg"
          alt="nothing unusual down here."
        />
      </div>
    </div>
  </div>
</template>

<script>
import Social from "../components/Social.vue";
export default {
  components: {
    Social
  }
};
</script>

<style></style>
