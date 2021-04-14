<template>
  <div class="bg-accent pb-5">
    <div class="mx-auto max-w-screen-lg">
      <h1 class="text-primary text-center font-bold text-5xl">
        <span>Minato</span> <span class="text-primary-light">Aqua</span>
        <span class="text-secondary">Virtual</span>
        <span class="text-white">Shrine</span>
      </h1>
      <p class="text-black text-center mt-5">
        This website is a work in progress, feel free to checkout the
        <a href="https://github.com/KevinHaeusler/minato-aqua.vshrine.com"
          >Github</a
        >
      </p>
      <div class="lg:flex mt-5 lg:place-content-center">
        <div class="w-40 h-40 mr-5 bg-primary text-white text-center shadow">
          Primary
        </div>
        <div
          class="w-40 h-40 mr-5 bg-primary-light text-white text-center shadow"
        >
          Primary Light
        </div>
        <div class="w-40 h-40 mr-5 bg-secondary text-white text-center shadow">
          Secondary
        </div>
        <div class="w-40 h-40 mr-5 bg-accent text-black text-center shadow">
          Accent
        </div>
        <div class="w-40 h-40 mr-5 bg-white text-black text-center shadow">
          White
        </div>
      </div>
      <div class="flex mt-5">
        <bgm class="mx-auto" />
      </div>
      <img
        class="mx-auto"
        :src="require(`~/assets/img/costumes/minatoaqua-default.png`)"
      />
      <div class="bg-primary max-w-screen-md mx-auto p-5">
        <iframe
          class="mx-auto"
          width="360"
          height="202"
          src="https://www.youtube.com/embed/O8v5S1nhKzo"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>
  </div>
</template>

<script>
import Bgm from '~/components/Bgm.vue'
export default {
  components: { Bgm }
}
</script>

<style>
a {
  @apply font-bold text-secondary hover:text-pink-200;
}
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
