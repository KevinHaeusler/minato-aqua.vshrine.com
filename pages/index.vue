<template>
  <div class="pb-5 bg-accent">
    <div class="mx-auto">
      <h1 class="text-5xl font-bold text-center text-primary">
        <span>Minato</span> <span class="text-primary-light">Aqua</span>
        <span class="text-secondary">Virtual</span>
        <span class="text-white">Shrine</span>
      </h1>
      <p class="mt-5 text-center text-black">
        This website is a work in progress, feel free to checkout the
        <a href="https://github.com/KevinHaeusler/minato-aqua.vshrine.com"
          >Github</a
        >
      </p>
      <div class="mt-5 lg:flex lg:place-content-center">
        <div class="w-40 h-40 mr-5 text-center text-white shadow bg-primary">
          Primary
        </div>
        <div
          class="w-40 h-40 mr-5 text-center text-white shadow bg-primary-light"
        >
          Primary Light
        </div>
        <div class="w-40 h-40 mr-5 text-center text-white shadow bg-secondary">
          Secondary
        </div>
        <div class="w-40 h-40 mr-5 text-center text-black shadow bg-accent">
          Accent
        </div>
        <div class="w-40 h-40 mr-5 text-center text-black bg-white shadow">
          White
        </div>
      </div>
      <br /><br /><br /><br /><br /><br /><br /><br /><br />
      <Costumes />

      <br /><br /><br /><br /><br /><br /><br /><br /><br />
      <div class="flex mt-5">
        <bgm class="mx-auto" />
      </div>
      <img
        class="mx-auto"
        :src="require(`~/assets/img/costumes/minatoaqua-default.png`)"
      />
      <div class="max-w-screen-md p-5 mx-auto bg-primary">
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
