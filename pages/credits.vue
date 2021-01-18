<template>
  <div class="wrapper-small">
      <div class="text-center mt-2 border-b-2 pb-3">
        <h3 class="text-xl md:text-2xl lg:text-3xl text-gray-700 font-semibold">Credits.</h3>
        <h3 class="text-sm md:text-base text-gray-600 font-semibold max-w-lg mx-auto my-3">My sincere thanks to all the creators and maintainers of all the resources i used for building this template. Special shoutout for making all these resources free and open-source.</h3>
      </div>
      <div class="flex justify-center content-center px-5">
        <ul class="list-disc">
            <li class="credit-item">Frontend Framework : <a href="https://nuxtjs.org/" class="credit-link">Nuxt.js</a></li>
            <li class="credit-item">CMS: <a href="https://www.netlifycms.org/" class="credit-link">Netlify CMS</a></li>
            <li class="credit-item">CSS library : <a href="https://tailwindcss.com/" class="credit-link">Tailwind CSS</a></li>
            <li class="credit-item">Tailwind Components : <a href="https://merakiui.com/" class="credit-link">Meraki UI</a></li>
            <li class="credit-item">Icons : <a href="https://boxicons.com/" class="credit-link">Boxicons</a></li>
            <li class="credit-item">Useful code snippets : <a href="https://nuxtjs.org/blog/creating-blog-with-nuxt-content/#live-editing-our-content" class="credit-link">Blog Post</a> By <a href="https://twitter.com/debs_obrien" class="credit-link">Debbie O'Brien</a></li>
        </ul>
      </div>
      <div class="mt-8 text-center">
        <h3 class="text-lg md:text-xl text-gray-700 font-semibold text-center">You can follow me here.</h3>
        <a class="social-link hover:text-primary" href="https://github.com/dev-ggaurav" aria-label="Github">
          <i class='bx bxl-github'></i>
        </a>

        <a class="social-link hover:text-primary" href="https://twitter.com/devggaurav" aria-label="Twitter">
          <i class='bx bxl-twitter'></i>
        </a>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
    .credit-item{
        @apply text-lg mb-5 text-gray-800 font-semibold;
    }

    .credit-link{
        @apply text-primary;
    }
</style>