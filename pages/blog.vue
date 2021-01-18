<template>
  <div class="wrapper-small md:px-10">
    <div class="text-center mt-2 border-b-2 pb-3">
      <h3 class="text-xl md:text-2xl lg:text-3xl text-gray-700 font-semibold">Welcome to my blog.</h3>
    </div>
    <div class="my-10 bg-gray-100 p-4 md:p-6 rounded-xl shadow-md">
      <div class="flex justify-between items-center">
        <span class="font-semibold text-gray-600 text-sm">Date</span>
        <span class="px-3 py-1 bg-gray-600 text-white text-sm font-bold rounded">Tag</span>
      </div>

      <div class="mt-2">
        <a
          class="text-xl md:text-2xl text-gray-700 font-bold hover:text-gray-600 hover:underline">Title
        </a>
        <p class="mt-2 text-base lg:text-lg text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam quos fuga omnis nihil? Dignissimos, inventore labore assumenda quae optio, neque tempore consequatur similique provident, eum consequuntur eveniet repellat eaque tenetur!</p>
      </div>

      <div class=" mt-4">
        <a class="text-primary font-semibold hover:underline">Read more</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  //   methods:{
  //   formatDate(date) {
  //     const options = { year: 'numeric', month: 'long', day: 'numeric' }
  //     return new Date(date).toLocaleDateString('en', options)
  //   }
  // },
}
</script>

<style>

</style>