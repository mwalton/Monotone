<template>
  <div class="wrapper text-center text-gray-700 mb-8">
    <a
      class="social-link hover:text-primary"
      href="https://github.com/mwalton"
      target="_blank"
      aria-label="Github"
    >
      <i class="bx bxl-github"></i> Code
    </a>

    <a
      class="social-link hover:text-primary"
      href="https://scholar.google.com/citations?user=TTEHCqUAAAAJ&hl=en"
      target="_blank"
      aria-label="Scholar"
    >
      <i class="bx bxs-graduation"></i> Papers
    </a>

    <nuxt-link class="social-link hover:text-primary" to="blog">
      <i class="bx bxs-pencil"></i> Notes
    </nuxt-link>
  </div>
</template>

<script>
export default {};
</script>

<style>
.social-link {
  @apply mx-3 text-2xl text-gray-800;
}
</style>
