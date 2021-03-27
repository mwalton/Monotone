<template>
  <div class="wrapper-small">
    <div
      class="my-10 bg-gray-100 p-4 md:p-6 rounded-xl shadow-md"
      v-for="post of posts"
      :key="post.slug"
    >
      <div class="mt-2">
        <div class="flex flex-col md:flex-row md:space-x-10 items-center">
          <img :src="post.img" class="rounded-md w-64 md:w-32" alt="derp" />
          <div>
            <a
              class="text-md md:text-2xl text-gray-700 font-bold hover:text-gray-600 hover:underline"
              target="_blank"
              :href="post.url"
            >
              {{ post.organization }}
            </a>
            <p class="mt-2 text-base text-md md:text-lg text-gray-600">
              {{ post.position }} • {{ post.time }}
            </p>
            <p class="mt-2 text-base text-md md:text-lg text-gray-600">
              {{ post.location }}
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    components: {},
    data() {
      return { posts: {} };
    },
    async fetch() {
      this.posts = await this.$content("affiliations")
        .sortBy("order")
        .fetch();
    }
  };
</script>

<style></style>
