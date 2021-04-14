<template>
  <div
    class="grid max-w-screen-lg grid-cols-1 mx-auto shadow bg-primary lg:grid-cols-2"
  >
    <div class="w-10/12 mx-auto">
      <div class="md:-mx-3 bg-primary-light">
        <VueSlickCarousel :arrows="true" :dots="false">
          <div>
            <p class="text-3xl font-bold text-center text-white">
              Default Costume
            </p>
            <img
              class="mx-auto"
              :src="require(`~/assets/img/costumes/minatoaqua-default.png`)"
            />
          </div>
          <div>
            <p class="text-3xl font-bold text-center text-white">
              New Years Costume
            </p>
            <img
              class="mx-auto"
              :src="require(`~/assets/img/costumes/minatoaqua-newyear.png`)"
            />
          </div>
        </VueSlickCarousel>
      </div>
    </div>
    <div class="text-center bg-white">
      <p class="text-3xl font-bold text-secondary">Costumes</p>
      <p>Testing some Sliders for costumes</p>
      <br /><br />
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi quibusdam
        perferendis ducimus ut. Unde ut nostrum beatae, aspernatur dignissimos
        vel corporis eaque incidunt temporibus soluta ea facere minima rem
        cumque.
      </p>
    </div>
  </div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default { name: 'MyComponent', components: { VueSlickCarousel } }
</script>

<style></style>
