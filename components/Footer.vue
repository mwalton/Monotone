<template>
  <div class="wrapper mx-auto px-10">
      <hr class="h-px mt-6 border-gray-300 max-w-screen-xl mx-auto">
      <div class="md:py-10">
            <div class="flex flex-col items-center justify-between mt-6 md:mt-0 md:flex-row">
                <div class="logo">
                  <nuxt-link to="/">
                    <h1 class="text-gray-700">
                        <span class="text-primary text-xl font-serif">{τhϵorγ}</span> &
                        <span class="font-mono">praxis( )</span>
                    </h1>

                  </nuxt-link>
                </div>

                <div>
                    <Social />
                </div>
                <div>
                    <img src = "~/assets/nothing_unusual.svg" alt="nothing unusual down here."/>
                </div>
            </div>
        </div>
  </div>
</template>

<script>
import Social from '../components/Social.vue'
export default {
    components: {
        Social
    }
}
</script>

<style>

</style>