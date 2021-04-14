<template>
  <button class="bg-secondary rounded p-4 shadow text-white" @click="playSound">
    Destroy Braincells
  </button>
</template>

<script>
export default {
  data() {
    return {
      audio: null
    }
  },
  methods: {
    playSound() {
      this.audio = new Audio(require(`~/assets/audio/bg.mp3`))
      this.audio.play()
    }
  }
}
</script>

<style></style>
