<template>
  <div class="my-8 max-w-lg mx-auto">
    <input
      v-model="searchQuery"
      type="search"
      autocomplete="off"
      placeholder="Search notes"
      class="w-full bg-gray-300 text-gray-900 mt-2 p-3 rounded-lg focus:outline-none"
    />
    <ul
      v-if="posts.length"
      class="z-10 absolute w-auto flex-1 top-40 bg-white rounded-md border border-gray-300 overflow-hidden"
    >
      <li v-for="post of posts" :key="post.slug">
        <nuxt-link
          :to="post.slug"
          class="flex px-4 py-2 items-center leading-5 transition ease-in-out duration-150 text-primary hover:text-black"
        >
          {{ post.title }}
        </nuxt-link>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  data() {
    return {
      searchQuery: "",
      posts: []
    };
  },
  watch: {
    async searchQuery(searchQuery) {
      if (!searchQuery) {
        this.posts = [];
        return;
      }
      this.posts = await this.$content("blog")
        .limit(6)
        .search(searchQuery)
        .fetch();
    }
  }
};
</script>
