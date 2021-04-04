<template>
  <div class="wrapper mx-auto px-10">
    <hr class="h-px mt-6 border-gray-300 max-w-screen-xl mx-auto" />
    <div class="md:py-10">
      <div
        class="flex sm: flex-col lg:flex-row md:flex-col items-center justify-between mt-6 pb-3"
      >
        <div>
          <Social />
        </div>

        <img
          class="object-scale-down w-48"
          src="~/assets/nothing_unusual.svg"
          alt="nothing unusual down here...."
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
